# Zoe Guy

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Zoe Guy")
sort date DESC

```