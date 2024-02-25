ToDo List Version 4

Welcome to ToDo List Version 4! This is a web application designed to help you organize your tasks efficiently. Below you'll find detailed information about the project's characteristics, data structure, functionalities, and views/reports.

Basic Characteristics

No User Identification Needed: You can start managing your tasks without the need for user authentication.
Tasks Visibility: The current user can view all tasks.
Data Structure

Tasks
Each task includes:

Task Description: A brief description of the task (required).
Due Date: The deadline for completing the task (required).
Task Category: An optional categorization for the task.
Priority Level: An optional priority level ranging from 1 to 4, with 1 being the highest priority.
Status: Indicates whether the task is active or completed.
Categories
Each task category consists of:

Name: The name of the category.
Parent Category: Another existing category which serves as the parent category. If the current category is already a parent category, this attribute cannot be modified.
Functionalities

Task Management: The current user can create tasks and mark them as completed.
Category Management: Users can create and edit categories, including subcategories.
Views or Reports: Various views and reports are available to provide insights into task completion and overdue tasks.
Views or Reports

Default List View: Displays overdue tasks and tasks due today, sorted by priority.
Completed Tasks View: Allows the user to see completed tasks on a specific day, sorted by due date.
Weekly Report: Provides a summary of tasks completed each day within a specific week, including the total number of tasks completed.

