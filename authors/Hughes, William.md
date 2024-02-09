# William Hughes

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "William Hughes")
sort date DESC

```