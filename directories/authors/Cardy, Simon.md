# Simon Cardy

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Simon Cardy")
sort date DESC

```