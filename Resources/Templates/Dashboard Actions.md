
`BUTTON[new-jot-btn]`  `BUTTON[new-note-btn]`  `BUTTON[new-task-btn]`  `BUTTON[new-area-btn]`  `BUTTON[new-project-btn]`  `BUTTON[new-canvas-btn]` `BUTTON[new-drawing-btn]`

```meta-bind-button
label: New Jot
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: "A quick note"
id: "new-jot-btn"
hidden: true
actions:
  - type: templaterCreateNote
    templateFile: Resources/Templates/Jot.md
    folderPath: Notes/Jots
    fileName: ""
    openNote: true
    openIfAlreadyExists: false

```
```meta-bind-button
label: New Note
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: "Create a full note"
id: "new-note-btn"
hidden: true
actions:
  - type: templaterCreateNote
    templateFile: Resources/Templates/Note.md
    folderPath: Notes
    fileName: ""
    openNote: true
    openIfAlreadyExists: false

```
```meta-bind-button
label: New Task
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: "Create a task"
id: "new-task-btn"
hidden: true
actions:
  - type: templaterCreateNote
    templateFile: Resources/Templates/Task.md
    folderPath: Notes/Tasks
    fileName: ""
    openNote: true
    openIfAlreadyExists: false

```
```meta-bind-button
label: New Area
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: "Create an area"
id: "new-area-btn"
hidden: true
actions:
  - type: templaterCreateNote
    templateFile: Resources/Templates/Area.md
    folderPath: Areas
    fileName: ""
    openNote: true
    openIfAlreadyExists: false

```
```meta-bind-button
label: New Project
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: "Create a project"
id: "new-project-btn"
hidden: true
actions:
  - type: templaterCreateNote
    templateFile: Resources/Templates/Project.md
    folderPath: Notes/Projects
    fileName: ""
    openNote: true
    openIfAlreadyExists: false

```
```meta-bind-button
label: New Canvas
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: "Create a diagram"
id: "new-canvas-btn"
hidden: true
actions:
  - type: templaterCreateNote
    templateFile: Resources/Templates/Canvas.canvas
    folderPath: Resources/Canvas
    fileName: ""
    openNote: true
    openIfAlreadyExists: false

```
```meta-bind-button
label: New Drawing
icon: ""
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: "Create a drawing"
id: "new-drawing-btn"
hidden: true
actions:
  - type: command
    command: obsidian-excalidraw-plugin:excalidraw-autocreate-newtab


```