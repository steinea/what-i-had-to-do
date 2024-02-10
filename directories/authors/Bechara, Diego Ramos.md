# Diego Ramos Bechara

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Diego Ramos Bechara")
sort date DESC

```