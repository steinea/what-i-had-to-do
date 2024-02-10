# Rebekah Valentine

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Rebekah Valentine")
sort date DESC

```