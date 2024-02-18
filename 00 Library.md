---
tags: log
---

# Books Library

```dataview
table Author, Cover
from "Books"
```


```dataview
table rows.file.link as Book
from "Books"
group by Status
sort Status
```
