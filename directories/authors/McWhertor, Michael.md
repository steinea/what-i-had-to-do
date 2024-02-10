# Michael McWhertor

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Michael McWhertor")
sort date DESC

```