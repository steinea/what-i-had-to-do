# Carolyn Giardina

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Carolyn Giardina")
sort date DESC

```