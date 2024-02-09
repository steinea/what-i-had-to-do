# Nick Romano

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Nick Romano")
sort date DESC

```