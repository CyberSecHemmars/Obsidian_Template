---

tags: [Daily, {{date:dddd}}]
---
## DAILY NOTE
#### {{date:dddd, MMMM Do, YYYY}}.
<<= [[<% tp.date.now("YYYY-MM-DD", -1) %>|Yesterday]] <<= [[<% tp.date.now("YYYY-MM-DD") %>|Today]] =>> [[<% tp.date.now("YYYY-MM-DD", 1) %>|Tomorrow]] =>>

### JOURNAL
***


### TASKS 
***
- [ ] ...

### INCOMPLETE TASK
***
```tasks
path includes {06} - DAILY
not done
short mode
sort by due
hide tags
hide task count
```

### REVIEW
***
```dataview
TABLE
file.path as "Path"
FROM "/"
SORT file.name ASC
WHERE contains(file.tags, "#Review") and !contains(file.folder, "{99} - META")
```
