# Jen Glennon

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Jen Glennon")
sort date DESC

```