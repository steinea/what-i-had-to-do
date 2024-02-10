# Adam Bankhurst

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Adam Bankhurst")
sort date DESC

```