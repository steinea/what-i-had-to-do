# Matt Wales

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Matt Wales")
sort date DESC

```