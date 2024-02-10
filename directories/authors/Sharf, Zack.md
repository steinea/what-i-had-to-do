# Zack Sharf

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Zack Sharf")
sort date DESC

```