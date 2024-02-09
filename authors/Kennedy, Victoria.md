# Victoria Kennedy

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Victoria Kennedy")
sort date DESC

```