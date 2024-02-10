# Lesley Goldberg

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Lesley Goldberg")
sort date DESC

```