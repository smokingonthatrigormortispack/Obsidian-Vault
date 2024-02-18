---
tags: log
---

# Daily Notes Hub

💡 [[00 New Discoveries Log | New Discoveries]] | 🛳️ [[00 Ship's Log|Ship's Log]] | 📚 [[00 Media Log | Media Log]] | 🏋️ [[00 Workout Log | Workout Log]]

  

Summaries of the daily notes go here!

  
  
  
  

## This Week

---

```dataview

TABLE WITHOUT ID link(file.link, " ") + "<strong>" + Title + "</strong><br>" + Summary  + "<br>" + file.link AS Entries

from "Diary/Daily Notes"

SORT file.name desc

LIMIT 7

```

  
  
  
  
  

## Archive List

---

### 2023

```dataview

TABLE WITHOUT ID link(file.link, " ") + "<strong>" + Title + "</strong><br>" + Summary  + "<br>" + file.link AS Entries

from "Diary/Daily Notes"

WHERE file.day >= date(2023-01-01) AND file.day <=date(2023-12-31)

SORT file.name desc

````

