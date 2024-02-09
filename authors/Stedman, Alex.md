# Alex Stedman

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Alex Stedman")
sort date DESC

```