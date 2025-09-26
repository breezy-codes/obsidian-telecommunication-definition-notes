---
title: 02 All Definitions MOC
date created: Sunday, September 21st 2025, 12:16:30 pm
date modified: Sunday, September 21st 2025, 1:02:21 pm
cssclasses:
  - my-custom-style
---

## Main Categories
```dataviewjs
let cats = dv.pages("#telecommunications/definitions")
  .flatMap(p => p.file.tags
    .filter(t => t.startsWith("#telecommunications/definitions/"))
    .map(t => t.replace(/^#telecommunications\/definitions\/([^/]+).*$/, "$1"))
  );

let uniqueCats = [...new Set(cats)].sort().join(", ");
dv.paragraph(uniqueCats);

let defs = dv.pages("#telecommunications/definitions");
dv.paragraph("**Total definition files:** " + defs.length);

```

```dataviewjs
for (let group of dv.pages("#telecommunications/definitions")
  .flatMap(p => {
    // get all category tags for this page
    let cats = p.file.tags
      .filter(t => t.startsWith("#telecommunications/definitions/"))
      .map(t => t.replace(/^#telecommunications\/definitions\/([^/]+).*$/, "$1"));
    // dedupe category names per page
    return [...new Set(cats)].map(c => ({ page: p, category: c, allCats: [...new Set(cats)] }));
  })
  .groupBy(k => k.category)
  .sort(k => k.key, 'asc')) {

  dv.header(2, group.key); // ## Category

  dv.table(
    ["File", "Aliases", "Categories", "Subcategories"],
    group.rows.map(r => {
      let aliases = r.page.aliases ? r.page.aliases.join(", ") : "";

      // get sub-categories (after current category)
      let subcats = r.page.file.tags
        .filter(t => t.startsWith("#telecommunications/definitions/" + r.category + "/"))
        .map(t => t.replace(new RegExp("^#telecommunications/definitions/" + r.category + "/"), ""))
        .join(", ");

      // show all other categories this file belongs to (excluding current one)
      let otherCats = r.allCats.filter(c => c !== r.category).sort().join(", ");

      return [r.page.file.link, aliases, otherCats, subcats];
    })
    // dedupe rows so the same file doesn't appear multiple times
    .filter((row, idx, arr) => idx === arr.findIndex(r2 => r2[0].path === row[0].path))
  );
}
```

