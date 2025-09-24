# TODO.md

TODOs in a format similar to [TODO.txt](https://github.com/todotxt/todo.txt) but optimised for Markdown readability.

## Example

- [x] (A) Create an example +TODO  
  The example +TODO should provide demonstrate all fields and default tags @work  
  a:2025-09-08 d:2025-09-09 due:2025-09-09  

## Format

- [ ] Title line  
  Description line (optional)  
  Metadata (optional)  

### Title line

Status is recorded inside square brackets using markdown task markers:

- [ ] open
- [x] complete
- [o] cancelled or abandoned

Title can start with optional priority tag e.g. (A) for ordering higher priority tasks.
Title text can contain +project and @context tags as in TODO.txt. 

### Description line

Additional context or updates on the task, can include +project and @context
tags. Can span multiple lines if required.

### Metadata

Optional metadata in key:value format. Some default known metadata properties
include:

- a or added - When the todo was added, e.g. a:2025-09-08
- d or done - When the todo was done or completed e.g. d:2025-09-09
- due - Due date for the todo, e.g. due:2025-09-09
