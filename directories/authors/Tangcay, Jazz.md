# Jazz Tangcay

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Jazz Tangcay")
sort date DESC

```
