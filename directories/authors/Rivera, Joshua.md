# Joshua Rivera

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Joshua Rivera")
sort date DESC

```