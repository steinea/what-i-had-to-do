# Jarrod Jones

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Jarrod Jones")
sort date DESC

```