# Task Management

## Overview
This feature allows users to create, update, delete, and organize tasks. Each task can have subtasks and be categorized into folders.

## Requirements

### Task Creation
- User must be able to create tasks with the following attributes:
  - **Name** (mandatory, string, 255 characters max).
  - **Attribute** (optional, from 0 to 100, user-selectable)
- Task can be created in general folder, subfolder, or in another task.
- User can save **[[template]]** from current task.

### Attributes selection
- User must select type of attribute
- User must enter name of the attribute on the left
- User must enter value of the attribute on the right
  
### Task Editing
- User can update any attribute of a task.
- User can add any additional attribute
- User can delete any additional attribute
- User can move task from one task in another.
- User can save **[[template]]** from current task.
  
### Task Deletion
- Users must be able to delete tasks.
  - A confirmation prompt must be shown before deletion.
  - Deleting a task will also delete all associated subtasks.
  - Deleting a task will also delete all associated goals.

### Task Organization
- Tasks must be categorized into **folders**.
  - Tasks must be assigned to one folder but can be moved between folders.
- Users can move tasks from folder in task
- Users can move tasks from another task in folder

### Task Overview
- User can see all folders and tasks.
- User can see all tasks in folders.
- User can see all subtasks in tasks.

