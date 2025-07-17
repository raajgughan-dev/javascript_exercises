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


