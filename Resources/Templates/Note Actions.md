
>[!tip]- Note Actions 
> `BUTTON[new-task-btn]`  `BUTTON[new-excalidraw-btn]` `BUTTON[new-ink-section-btn]`  `BUTTON[new-ink-drawing-btn]`

```meta-bind-button
label: New Task
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: "Add a task"
id: "new-task-btn"
hidden: true
actions:
  - type: insertIntoNote
    line: 16
    value: "- [ ] "

```
```meta-bind-button
label: New Drawing
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: "Embed Excalidraw"
id: "new-excalidraw-btn"
hidden: true
actions:
  - type: command
    command: obsidian-excalidraw-plugin:excalidraw-autocreate-and-embed-on-current

```
```meta-bind-button
label: New Handwriting Section
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: "Create a handwriting section"
id: "new-ink-section-btn"
hidden: true
actions:
  - type: command
    command: ink:create-handwritten-section
```
```meta-bind-button
label: New Drawing Section
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: "Create a drawing section"
id: "new-ink-drawing-btn"
hidden: true
actions:
  - type: command
    command: ink:create-drawing-section
```

