# Eve Batey

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Eve Batey")
sort date DESC

```