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

<img width="610" height="714" alt="image" src="https://github.com/user-attachments/assets/dc015487-03f9-4f96-a742-a784ed4e79b0" />
<img width="600" height="529" alt="image" src="https://github.com/user-attachments/assets/90fe1ef1-5c96-4cb9-8aeb-609d27130b1c" />
<img width="584" height="553" alt="image" src="https://github.com/user-attachments/assets/3b28b70c-ff26-49f5-bff5-827833406e3b" />
<img width="591" height="393" alt="image" src="https://github.com/user-attachments/assets/b6aecec8-aa56-4fe7-a7b1-9fda1ef0814e" />

