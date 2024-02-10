# Alyssa Mercante

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Alyssa Mercante")
sort date DESC

```