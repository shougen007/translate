>[!Added]
```dataview
TABLE without id
	("![|50](" + image_url + ")") as "image",
	file.link as "book_title",
	author,
	pages,
	published,
	ratings
FROM "book"
WHERE status="added"
```

>[!Reading]
```dataview
TABLE without id
	("![|50](" + image_url + ")") as "image",
	file.link as "book_title",
	author,
	pages,
	published,
	ratings
FROM "book"
WHERE status="reading"
```
>

>[!Read]
```dataview
TABLE without id
	("![|50](" + image_url + ")") as "image",
	file.link as "book_title",
	author,
	pages,
	published,
	ratings
FROM "book"
WHERE status="read"
```
