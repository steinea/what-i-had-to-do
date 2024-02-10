# Jordan Moreau

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Jordan Moreau")
sort date DESC

```