# Oliver Mackenzie

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Oliver Mackenzie")
sort date DESC

```