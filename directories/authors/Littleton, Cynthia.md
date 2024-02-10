# Cynthia Littleton

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Cynthia Littleton")
sort date DESC

```