# Rosy Cordero

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Rosy Cordero")
sort date DESC

```