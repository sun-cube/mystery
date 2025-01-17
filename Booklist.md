```dataview
table without id
publication_year as "Year", author as "Author", title as "Title", file.link as "Link"
where contains(file.frontmatter, "author")
sort publication_year desc, author
```
