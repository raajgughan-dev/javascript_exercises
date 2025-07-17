![JavaScript Background](image/javascript.png)
# JavaScript Web App Development Exercises
These exercises are designed to help you practice JavaScript in the context of building interactive web applications. They cover concepts from basic DOM manipulation to more advanced data handling and asynchronous operations.

## Beginner Level Web App Exercises
These exercises focus on fundamental DOM manipulation, event handling, and basic user interaction.

1. Simple Counter App:
    * **Goal**: Create a web page with a display for a number, a "Increment" button, and a "Decrement" button.

    * **Requirements**: 
        * The number should start at 0.
        * Clicking "Increment" increases the number by 1.
        * Clicking "Decrement" decreases the number by 1.
        * Ensure the number never goes below 0.

2. Basic To-Do List:
    * **Goal**: Build a simple to-do list where users can add items.

    * **Requirements**: 
        * An input field for new tasks.
        * An "Add Task" button.
        * A list (<unorderlist(ol)> or <orderlist(ol)>) to display tasks.
        * When the "Add Task" button is clicked, the text from the input field should be added as a new list item.
        * Clear the input field after adding a task.

3. Image Carousel (Manual):
    * **Goal**: Create a simple image slider with "Next" and "Previous" buttons.

    * **Requirements**: 
        * Display one image at a time.
        * Have at least 3-5 images.
        * "Next" button displays the subsequent image in the sequence (loop back to the first after the last).
        * "Previous" button displays the preceding image in the sequence (loop back to the last after the first).

4. Color Changer:
    * **Goal**: Create a page where clicking a button changes the background color of the <body>.

    * **Requirements**: 
        * A button labeled "Change Color".
        * When clicked, the background color should change to a random color or cycle through a predefined list of colors.

5. Text Resizer:
    * **Goal**: Allow users to increase or decrease the font size of a paragraph of text.

    * **Requirements**: 
        * A paragraph of sample text.
        * An "Increase Font" button.
        * A "Decrease Font" button.
        * Clicking the buttons should change the font size of the paragraph (e.g., by 2px each time).
        * Set reasonable minimum and maximum font sizes.


# Intermediate Level Web App Exercises
These exercises involve more dynamic content, form handling, basic data persistence (client-side), and slightly more complex UI interactions.

1. Dynamic Quiz App:
    * **Goal**: Create a simple multiple-choice quiz.
    * **Requirements**:
        * Store quiz questions and answers in a JavaScript array of objects.
        * Display one question at a time with multiple choice options (radio buttons).
        * A "Submit Answer" button.
        * Provide immediate feedback (correct/incorrect) after submission.
        * Keep track of the score and display it at the end.
        * Allow users to restart the quiz.

2. Filterable Product List:
    * **Goal**: Display a list of products and allow users to filter them by category or search term.
    * **Requirements**: 
        * An array of product objects (e.g., { name: "Laptop", category: "Electronics", price: 1200 }).
        * Display all products initially.
        * An input field for searching by product name.
        * A dropdown/buttons for filtering by category.
        * Update the displayed list dynamically as the user types or selects filters.

3. Local Storage To-Do List:
    * **Goal**: Enhance the basic to-do list to save and load tasks using localStorage.
    * **Requirements**: 
        * All features from the basic to-do list.
        * Tasks should persist even if the browser is closed and reopened.
        * Implement a "Delete" button next to each task.
        * Implement a "Mark Complete" checkbox/button next to each task.

4. Form Validator:
    * **Goal**: Create a simple registration form and validate its inputs.
    * **Requirements**:
        * Fields for Username, Email, Password, Confirm Password.
        * "Submit" button.
            * Username: Minimum 3 characters.
            * Email: Valid email format (simple regex check).
            * Password: Minimum 6 characters.
            * Confirm Password: Must match Password.
        * Display error messages next to invalid fields without submitting the form if validation fails.

5. Countdown Timer:
    * **Goal**: Build a countdown timer that counts down to a specific date/time or from a user-defined duration.
    * **Requirements**: 
        * Input fields for hours, minutes, seconds (or a target date/time).
        * "Start", "Pause", "Reset" buttons.
        * Display the remaining time in HH:MM:SS format.
        * Use setInterval and clearInterval.
        * Optionally, play a sound or show an alert when the timer reaches zero.

# Professional Level Web App Exercises
These exercises introduce more advanced concepts like asynchronous operations (simulated or real API calls), more complex state management, and building reusable components.

1. GitHub User Search (with API):
    * **Goal**: Create an application that fetches and displays GitHub user profiles.
    * **Requirements**: 
        * An input field for a GitHub username.
        * A "Search" button.
        * Use the GitHub Users API (https://api.github.com/users/{username}) to fetch data.
        * Display the user's avatar, name, public repos count, followers, and a link to their profile.
        * Implement error handling (e.g., user not found, network issues).
        * Show a loading indicator while fetching data.

2. Simple Shopping Cart:
    * **Goal**: Build a basic shopping cart system.
    * **Requirements**: 
        * Display a list of available products (array of objects with id, name, price)
        * "Add to Cart" button for each product.
        * A separate "Cart" section displaying items added, their quantity, and total price.
        * "Remove from Cart" button for items in the cart.
        * "Increase/Decrease Quantity" buttons in the cart.
        * Update totals dynamically.
        * (Optional) Persist cart data in localStorage.

3. Infinite Scroll/Lazy Loading:
    * **Goal**: Load content dynamically as the user scrolls down the page.
    * **Requirement**:
        * Simulate fetching more data (e.g., from an array or a setTimeout function).
        * Initially display a limited number of items.
        * When the user scrolls near the bottom of the page, automatically load and append more items.
        * Show a "Loading..." message at the bottom while new data is being fetched.
        * (Optional) Implement a "No more items" message when all data is loaded.

4. Drag-and-Drop Reorder List:
    * **Goal**: Create a list of items that can be reordered by dragging and dropping them.
    * **Requirements:**: 
        * A list of items (e.g., a <unorderlist(ul)> with <listitem(li)> elements).
        * Make each list item draggable.
        * Allow users to drag an item and drop it into a new position in the list.
        * Update the actual order of the items in the DOM.
        * (Hint: Use dragstart, dragover, dragleave, drop events).

5. Single Page Application (SPA) with Hash Routing:
    * **Goal**: Build a simple SPA with multiple "pages" (views) using hash-based routing.
    * **Requirements**: 
        * Create at least three distinct "pages" (e.g., Home, About, Contact).
        * Use <a> tags with href="#home", href="#about", etc., for navigation.
        * Implement JavaScript logic to listen for hashchange events.
        * Based on the URL hash, dynamically show/hide the corresponding content section, giving the impression of navigating between pages without a full page reload.
        * Ensure the initial view is correctly rendered based on the starting hash.
