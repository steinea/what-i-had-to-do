# Jen Chaney

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Jen Chaney")
sort date DESC

```