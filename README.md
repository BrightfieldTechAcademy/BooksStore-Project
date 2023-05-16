# BooksStore-Project
This is a project requirement for student at BTA to build a simple web application to manage books in their library

# BooksStore-Project
This is a project requirement for student at BTA to build a simple web application to manage books in their library

## Learning objective 🍎
  - Learn how to get user input form HTML form. 
  - Learn how to display data received HTML form to the UI.
  - Learn how to use `localStorage` to store data.
  - Learn how to use proper ES6 syntax.
  - Understand improvements that ES6 brings to JavaScript.
  - Understand how to use `class` and `object` in JavaScript.
  - Understand `addEventListener` method and how to use it.


## Project Requirements

### 1. Create a form to get user input 👏
  - Create a form to get user input
  - The form should have the following fields:
    - Book title
    - Author
    - ISBN (International Standard Book Number)
  - The form should have a submit button
  - The form should have a reset button
  - [optional] Add style to the form using CSS
  - [optional] Add validation to the form using JavaScript

### 2. Display data received from the form 👍
  - [ ] Display data received from the form to the UI :
      - How to read data from the form
         1. Get the form element
         2. Get the value of each input field and store it in a variable in the `submit` event handler in a form of an object `book`
      - How to display the data to the UI
         1. Get the table element in the DOM
         2. Create a new row and append it to the table
         3. Create a new cell for each field and append it to the row
         4. Set the value of each cell to the value of each field
  - [optional] Add style to the table using CSS

### 3. Store and get the data from the `localStorage` 🏪

#### What is `localStorage`?
    `localStorage` is a property of the `window` object. It allows you to store data in the browser. The data will not be deleted when the browser is closed. It will be deleted only when you clear the browser cache.

#### How to use the `localStorage`? 
  - [ ] How to store data to `localStorage`
      1. Convert the `book` object to a string using `JSON.stringify(book)`
      2. Use `localStorage.setItem('books', bookString)` to store the string to `localStorage`
  - [ ] How to get data from `localStorage`
      1. Use `localStorage.getItem('books')` to get the string from `localStorage`
      2. Convert the string to an object using `JSON.parse(bookString)`
      3. Display the data to the UI

- [ ] **PLEASE NOTE: 🙏 Before you get to the next step, you should have your application working properly. You should be able to add a book to the table and the data should be stored in the `localStorage`. You should be able to see the data in the table when you refresh the page**.

### 4. Delete a book from the table 😊
- [ ] Add a delete button to each row in the table
- [ ] Add an event listener to the delete button
- [ ] Delete the row from the table
- [ ] Delete the data from the `localStorage`
   
### 5. [optional] Add a search bar to the UI 💯
- [ ] Add a search bar to the UI
- [ ] Add an event listener to the search bar
- [ ] Filter the data in the table based on the search term
- [ ] Display the filtered data to the UI

