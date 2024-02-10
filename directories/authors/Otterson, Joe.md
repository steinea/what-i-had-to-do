# Joe Otterson

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Joe Otterson")
sort date DESC

```