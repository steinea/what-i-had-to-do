# Bryn Gelbart

[[authors]]

```dataview

TABLE publication, date
from "articles"
where contains(flat(list(author)), "Bryn Gelbart")
sort date DESC

```