# Rudie Obias

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Rudie Obias")
sort date DESC

```