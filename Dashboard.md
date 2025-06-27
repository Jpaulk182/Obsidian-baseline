---
icon-image: Resources/Images/Icons/Brain.svg
banner: "![[woodcuts_15.jpg]]"
banner_y: 0
cssclasses:
  - list-cards
banner-height: 500
icon-y: -100
icon-x: 0
created: 2025-06-25 21:50
modified: 2025-06-26 23:39
---
```meta-bind-embed
[[Dashboard Actions]]
```
> [!abstract]- Recent Jots
> ```dataview 
> table created, modified from "Notes/Jots" sort created desc limit 5
>```

> [!note]- Recent Notes
> ```dataview 
> table created, modified from "Notes" sort created desc limit 5
>```

> [!important]- Tasks
> ```dataview 
> table created, modified from "Notes/Tasks" sort created
>```

> [!question]- Recent Daily Notes
> ```dataview 
> table created, modified from "Notes/Calendar" sort created desc limit 5
>```

> [!example]- Projects
> ```dataview 
> table created, modified from "Notes/Projects" sort created
>```

> [!info]- Most Recent Objects
> ```dataview 
> table file.ctime as "created" where file.ctime sort file.ctime desc limit 10
>```
