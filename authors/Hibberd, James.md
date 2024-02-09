# James Hibberd

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "James Hibberd")
sort date DESC

```