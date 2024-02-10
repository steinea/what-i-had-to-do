# Katcy Stephan

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Katcy Stephan")
sort date DESC

```