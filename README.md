# React + Vite


Usage
Adding Tasks
To add a new task, type it in the input field and click the "Add Todo" button. The task will be added to the Redux store and displayed on the screen.

Marking Tasks as Complete
You can mark tasks as complete by clicking the checkbox next to each task. This will update the task state to completed in the Redux store.

Deleting Tasks
Tasks can be deleted by clicking the "Delete" button next to each task.

State Persistence
This app uses Redux to manage state. The state is persisted in localStorage so that it remains intact even after a page reload.

To implement persistence:
Add a middleware that syncs the Redux store with localStorage.
On app load, check if there's existing state in localStorage and rehydrate the Redux store with it.
Contributing
Feel free to fork this repository and create pull requests to improve the functionality, fix bugs, or enhance the UI. If you have suggestions or questions, open an issue!



