# Ari Notis

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Ari Notis")
sort date DESC

```