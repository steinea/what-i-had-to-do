# Ryan Dinsdale

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Ryan Dinsdale")
sort date DESC

```