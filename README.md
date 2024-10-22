# Task List

This application permits to keep track of tasks related to projects.
It already comes with the implemented features:
- `show`: list all the tasks divided by projects
- `add <project>`: add a new project:
- `add task <project> <task description>`: add a new task on a project
- `check <task id>`: mark a task as done

The code base is not in the best shape, there are new features that need to be
implemented, is up to you to decide if start by working on the new features or
to do some preparatory refactoring.

## Features

  1. Deadlines
      1. Give each task an optional deadline with the `deadline <ID> <date>` command.
      2. Show all tasks due today with the `today` command.
  2. Customizable IDs
      1. Allow the user to specify an identifier that's not a number.
      2. Disallow spaces and special characters from the ID.
  3. Deletion
      1. Allow users to delete tasks with the `delete <ID>` command.
  4. Views
      1. View tasks by date with the `view by date` command.
      2. View tasks by deadline with the `view by deadline` command.
      3. Don't remove the functionality that allows users to view tasks by project,
         but change the command to `view by project`.

## Notes

Feel free to follow the approach you feel most comfortable with, to verify the
working state of the application you can use the automated unit tests or by
manually running the main method in the `TaskList` class.
