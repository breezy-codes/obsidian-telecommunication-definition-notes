---
title: RAN Architectures & Components
date created: Friday, August 22nd 2025, 3:24:17 pm
date modified: Sunday, September 21st 2025, 4:39:26 pm
category: ran-architectures-and-components
cssclasses:
  - my-custom-style
---


# All Definitions

```dataview
TABLE join(aliases, ", ") AS "Aliases",
  join(
    unique(
      map(
        filter(
          file.tags,
          (t) => startswith(t, "#telecommunications/definitions/")
        ),
        (t) => regexreplace(t, "^#telecommunications/definitions/([^/]+).*", "$1")
      )
    ),
    ", "
  ) AS "Categories",
  join(
    map(
      filter(
        file.tags,
        (t) => contains(t, "#telecommunications/definitions/" + this.category + "/")
      ),
      (t) => regexreplace(t, "^#telecommunications/definitions/" + this.category + "/", "")
    ),
    ", "
  ) AS "Sub-categories"
FROM #telecommunications/definitions
WHERE contains(file.tags, "#telecommunications/definitions/" + this.category)
SORT file.name ASC
```
