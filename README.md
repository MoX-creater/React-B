## Library Management UI with Search, Add, and Remove Book Functionality
# Objective

The objective of this project is to build an interactive library management interface using React. Users can view a list of books and perform actions such as searching, adding, and removing books. This task reinforces the understanding of React state management, event handling, and dynamic rendering.

# Task Description

The project involves creating a React-based UI with the following features:

Display Books

Render a list of books, each showing a title and an author.

Search Functionality

Include a search input that filters books in real-time based on the title or author as the user types.

Add New Books

Provide an input form to add new books to the list dynamically.

The form should accept both title and author of the book.

Remove Books

Include a remove button next to each book to delete it from the list.

All actions should update the UI dynamically without requiring a page reload, demonstrating React's reactivity and efficient state handling.

# Implementation Details

State Management: Use React useState hook to manage the list of books and the current search query.

Event Handling: Handle input changes, form submission, and button clicks to update state.

Dynamic Rendering: Filter and map the books array to render the updated list based on user interactions.

Component Structure: You may use separate components for the search bar, book list, and book items for better modularity.

# Example Usage
// Example initial books
const initialBooks = [
  { title: "1984", author: "George Orwell" },
  { title: "The Great Gatsby", author: "F. Scott Fitzgerald" },
  { title: "To Kill a Mockingbird", author: "Harper Lee" }
];


Typing "great" in the search box filters the list to show only The Great Gatsby.

Adding a new book through the form dynamically updates the book list.

Clicking "Remove" next to a book deletes it instantly from the list.

# Expected Outcome

Users can view all books in a clean, organized list.

Search input filters books in real-time.

New books can be added dynamically, and any book can be removed without refreshing the page.

The UI remains responsive, demonstrating effective React state management and dynamic rendering.

<img width="1920" height="1080" alt="Screenshot 2025-09-18 020406" src="https://github.com/user-attachments/assets/7e47b0e0-c626-4f22-b898-969c0bf29016" />
