# Vikki Blake

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Vikki Blake")
sort date DESC

```