---
tags: log
---

<- [[00 Daily Notes Hub | Daily Notes Hub]]

# Ship's Log

💡 [[00 New Discoveries Log | New Discoveries]] | 📚 [[00 Media Log | Media Log]] | 🏋️ [[00 Workout Log | Workout Log]]  | ❗[[00 Tasks Log | Tasks Log]]

  

The Ship's Log is divided into two sections: **Life Happenings** and **Personal Projects**.

  

Life Happenings for any event and accomplishments made. Personal Projects is for anything related to a non-work project that you do (i.e. blog, YouTube video, streaming)

  
  
  
  

## Life Happenings

---

  

```dataview

table LifeEvent as "Log"

from "Diary/Daily Notes"

where contains(LifeEvent, "")

sort file.name desc

```

  

## Personal Projects

---

```dataview

table PersonalProjects as "Log"

from "Diary/Daily Notes"

where contains(PersonalProjects, "")

sort file.name desc

```