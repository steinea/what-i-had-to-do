# Adam B. Vary

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Adam B. Vary")
sort date DESC

```