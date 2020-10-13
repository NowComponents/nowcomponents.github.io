---
title:  "Todo"
author: "Brad Tilton"
---
[todo](https://github.com/NowComponents/todo) - Todo component that works with the Simple Todo app.
![Todo](./assets/images/todo.png)


This is a simple todo list component that uses multiple subcomponents to build a pretty todo list. 
NowExperience components used are httpEffect, now-alert, now-button, now-card, now-dropdown, now-heading, now-highlighted-value, now-input, now-loader, now-modal,now-textarea.

You can create new, complete, and cancel todos from the component. You can also edit & delete existing todos.
Also, you can cycle between todos in different states using the dropdown (Open/Complete/Cancelled)

The component works with a simple todo list app found here: github.com/bradtiltonnow/simple-todo.

Please check the issues for enhancement ideas or add some of your own.

![image](./assets/images/todo_v2.png)

Subcomponent details can be found below:

**1. new-todo-item component**
- Component which opens in now-modal & allows creating new todos
- Users can input todo content(textarea) & due date(datepicker)
![image](./assets/images/todo_v2_create.png)

**2. todo-item component**
- Created card layout to display each todo [Issue#2](https://github.com/NowComponents/todo/issues/2)
- Displays todo number, content, due date & state
- Todos can be Completed/Cancelled using the footer buttons
- Due date can be found in the bottom of the card (Due by "date"/Due anytime) [Issue#4](https://github.com/NowComponents/todo/issues/4)
- Todos can be edited (content & due date) [Issue#3](https://github.com/NowComponents/todo/issues/3)
![image](./assets/images/todo_v2_edit.png)
- Todos can be deleted (displays popup)
![image](./assets/images/todo_v2_delete.png)
