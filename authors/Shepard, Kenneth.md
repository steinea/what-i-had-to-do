# Kenneth Shepard

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Kenneth Shepard")
sort date DESC

```