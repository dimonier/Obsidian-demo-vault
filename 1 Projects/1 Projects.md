up:: [[Home]]

# Проекты
```dataview
LIST
from "1 Projects"
where (length(split(file.path, file.name)) = 3 AND contains(file.name, "1 Projects") = false)
``` 

A **project** is “a series of tasks linked to a goal, with a deadline.”

Examples include: Complete app mockup; Develop project plan; Execute business development campaign; Write blog post; Finalize product specifications; Attend conference

## Проектные задачи
```tasks
path includes 1 Projects
not done
sort by due
group by priority
```
