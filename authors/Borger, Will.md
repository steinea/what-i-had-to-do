# Will Borger

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Will Borger")
sort date DESC

```