# Claire Jackson

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Claire Jackson")
sort date DESC

```