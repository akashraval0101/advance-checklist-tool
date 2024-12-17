# Advanced Checklist Tool

This is an advanced checklist tool that allows users to manage tasks and subtasks effectively. It offers features like adding tasks, marking them as completed, adding notes, and organizing them through a three-dot menu. The tool also includes the ability to move tasks or subtasks up or down, save and load the checklist to/from a file, and track progress.

## Features:
- **Add Main Topic/Subtopic**: Add main tasks or subtasks easily.
- **Check/Uncheck Tasks**: Mark tasks as completed by checking the checkbox.
- **Expand/Collapse Subtopics**: Toggle the visibility of subtasks.
- **Move Tasks/Subtasks Up/Down**: Reorder tasks or subtasks using the "Move Up" and "Move Down" options in the three-dot menu.
- **Edit Tasks/Subtasks**: Modify the name or description of tasks and subtasks.
- **Remove Tasks/Subtasks**: Delete tasks or subtasks from the checklist.
- **Add Notes**: Add detailed notes to tasks for additional information.
- **Progress Tracker**: Automatically calculates and displays the percentage of completed tasks.
- **Save to File**: Save the current checklist as a JSON file.
- **Load from File**: Load an existing checklist from a JSON file.
  
## Installation

1. Download or clone the repository.
2. Open the `index.html` file in your browser to use the tool.

## How to Use:
- **Adding a Task**: Click on the "Add Main Topic" button to add a new main task.
- **Adding a Subtask**: Use the three-dot menu next to a task to add a subtask.
- **Checking/Unchecking a Task**: Click on the checkbox next to the task to mark it as completed.
- **Expand/Collapse Subtasks**: Click the "+" or "-" sign to expand or collapse the subtasks of a task.
- **Reordering Tasks**: Use the "Move Up" and "Move Down" options in the three-dot menu to reorder tasks or subtasks.
- **Edit a Task/Subtask**: Use the "Edit" option from the three-dot menu to modify the name or description.
- **Removing a Task/Subtask**: Use the "Remove" option from the three-dot menu to delete a task or subtask.
- **Adding Notes**: Use the "Add Notes" option to add detailed notes to any task or subtask.
- **Saving**: Click "Save" to save the checklist as a JSON file.
- **Loading**: Click "Load" to load a previously saved checklist from a JSON file.

## File Format:
The checklist is saved as a JSON file. Each item has the following structure:
```json
{
  "text": "Task name",
  "checked": false,
  "collapsed": false,
  "subItems": [
    {
      "text": "Subtask name",
      "checked": false,
      "collapsed": false,
      "subItems": [],
      "notes": ""
    }
  ],
  "notes": "Additional notes"
}
