# Sophie McEvoy

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Sophie McEvoy")
sort date DESC

```