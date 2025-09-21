# todolist-crud-testing

I performed a full quality assurance cycle on the to-do list website https://todolist.james.am/#/.

The goal was to make sure every CRUD function—adding, viewing, editing, and deleting tasks—worked correctly and consistently.

I created 46 thorough test cases covering both positive and negative scenarios:

Create: adding tasks with normal text, empty names, long text, and special characters.

Read: verifying tasks display correctly after refresh and across sessions.

Update: editing task names, changing completion status, and checking input validation.

Delete: removing single or multiple tasks, verifying they stay deleted after page refresh.

While executing these tests I reported three significant defects in Trello:

Task Count Mismatch: the “tasks left” number always shows one less than the real total.

Task Formatting Issue: spacing differs between view mode and edit mode when editing a task.

Filter Scroll Position: after switching the task filter, the scroll position jumps to the wrong place.

I documented all test cases and defects in Trello, organizing them into clear lists and cards to track execution and status.

This project demonstrates my ability to design and execute CRUD-based testing, identify and clearly document defects, and maintain a professional QA workflow using Trello.
