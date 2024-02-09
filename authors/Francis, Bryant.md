# Bryant Francis

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Bryant Francis")
sort date DESC

```