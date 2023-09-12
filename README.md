https://sudarshan34.github.io/AutoSave/

I have create this project using html css and js
In the js code here the autosaveText  refers the textarea element with the id 'autosaveText'.
Once, the page loads, it checks if there's previously saved text in local storage using localStorage.getItem,If there's saved text,
it sets the value of the autosaveText textarea to that text, allowing users to recover their previous input
An event listener is added to the autosaveText textarea using addEventListener(input)
When we  type or edit text in the textarea, this event is triggered.
The event handler function retrieves the current text from the textarea and stores it in local storage using localStorage.setItem.
This enables automatic text saving as the we type, ensuring it  won't lose the input even if it is  closed or  the page is refreshed
