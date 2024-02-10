# George Yang

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "George Yang")
sort date DESC

```