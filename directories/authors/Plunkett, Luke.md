# Luke Plunkett

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Luke Plunkett")
sort date DESC

```