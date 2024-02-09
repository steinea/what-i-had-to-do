# Primetimer Staff

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Primetimer Staff")
sort date DESC

```