# Adele Ankers-Range

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Adele Ankers-Range")
sort date DESC

```