# Ryan Gilliam

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Ryan Gilliam")
sort date DESC

```