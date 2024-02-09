# Savannah Walsh

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Savannah Walsh")
sort date DESC

```