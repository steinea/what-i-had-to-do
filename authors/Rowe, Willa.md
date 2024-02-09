# Willa Rowe

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Willa Rowe")
sort date DESC

```