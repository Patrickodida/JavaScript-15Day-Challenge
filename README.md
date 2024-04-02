## 15-Day JavaScript Challenge with GitLab

This 15-day challenge will help you improve your JavaScript skills while learning GitLab for version control. We'll be using GitLab to store and manage our code throughout the challenges.

**Before you begin:**

1. **Create a GitLab account:** If you don't have one already, head over to [https://about.gitlab.com/](https://about.gitlab.com/) and sign up for a free account.

2. **Find the Challenge Repository:** You'll need a starting point for your code. While there isn't an official repository for this specific challenge, you can find many similar JavaScript challenge repositories on GitLab. Search for "JavaScript 15 Day Challenge" or similar terms. 

3. **Fork the Repository:** Once you find a suitable repository, click the "Fork" button to create your own copy of the code in your GitLab account.

4. **Clone the Forked Repository (Optional):** This step allows you to work on the code locally on your computer. You can use Git commands or a Git desktop client for cloning. Refer to GitLab's documentation ([https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html](https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html)) for detailed instructions on cloning a repository. 

**Daily Challenge Workflow:**

1. **Create a Branch:**  For each day's challenge, it's recommended to create a separate branch to isolate your work. In your GitLab project, navigate to the "Branches" section and click "New branch." Name the branch after your name followed by "-dayX" (e.g., "yourname-day1").

2. **Create `main.js`:** Within your project directory (local or online), create a new JavaScript file named `main.js`. This will be your main working file for each day's challenges.

3. **Tackle the Daily Challenges:** Refer to the daily challenge descriptions (provided previously) and work on the problems within `main.js`.

4. **Commit Your Changes:** Once you've completed the day's challenges, commit your changes to your branch using Git commands or your Git client. 

5. **Push Your Changes (Optional):** If you cloned the repository locally, push your committed changes to your GitLab branch using `git push origin your-branch-name`.

6. **Repeat for Each Day:**  Follow steps 1-5 for each day of the challenge, creating a new branch and working on the problems in `main.js`.

**Additional Tips:**

* Use descriptive commit messages when committing your changes. This helps track your progress and understand changes later.
* Feel free to modify the challenges based on your interests and skill level. 
* Utilize online resources like JavaScript documentation ([https://developer.mozilla.org/en-US/docs/Web/JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)) and tutorials to deepen your understanding.
* Don't hesitate to seek help online on forums or communities dedicated to JavaScript and Git.

By following these steps and dedicating time each day, you'll gain a solid foundation in JavaScript and GitLab version control. Remember, consistency is key!


## Day 1: Introduction

**Welcome to the 15-Day JavaScript Challenge!**

This first day is all about setting the stage and getting familiar with the basic syntax of JavaScript. 

**Challenge 1: Hello World!**

Print the classic "Hello World!" message to the console.

**Challenge 2: Meet Yourself**

Declare three variables:

* `name` (string) to store your name
* `age` (number) to store your age
* `isExcited` (boolean) set to `true` if you're excited about the challenge

Print the values of these variables to the console using descriptive messages.

**Challenge 3: Age Check**

Write an if statement that checks if your age is greater than 18. If true, print "You're eligible to learn advanced concepts!" to the console.


## Day 2: Variables and Data Types

Today, we'll delve deeper into variables and explore different data types in JavaScript.

**Challenge 1: Multi-talented Variables**

Declare variables of the following data types and assign appropriate values:

* String (your favorite food)
* Number (current year)
* Boolean (true if you prefer coding in the day, false for night)

Print the variable type along with the assigned value for each variable. (Hint: use the `typeof` operator)

**Challenge 2: Mathematical Operations**

Declare two numeric variables and perform basic mathematical operations on them (addition, subtraction, multiplication, division). Print the results to the console.

**Challenge 3:  Mixing It Up**

Can you concatenate (join) a string and a number? Try creating a message like "The current year is: 2024".


## Day 3: Control Flow - If Statements

Conditional statements are crucial for making decisions in your code. Today's focus is on if statements.

**Challenge 1: Even or Odd?**

Write an if statement that takes a number as input (you can prompt the user using `prompt()`). Check if the number is even or odd and print the appropriate message to the console.

**Challenge 2: Grading System**

Imagine a grading system with letter grades based on scores. Write a series of if statements to assign letter grades (A, B, C, D, F) based on a given score (use `prompt()` for input).

**Challenge 3:  Discount Time!**

Write an if statement that checks if a purchase amount (use `prompt()` for input) exceeds a certain threshold (e.g., $100). If it does, apply a discount (e.g., 10%) and print the final price to the console. 

**(Remember these are just examples. Feel free to modify the challenges based on your interests!)**


## Day 4: Control Flow - Loops (For Loop)

Loops allow you to repeat a block of code multiple times. Today, we'll explore for loops.

**Challenge 1: Counting Up**

Write a for loop to print numbers from 1 to 10.

**Challenge 2: Counting Down**

Modify the previous loop to print numbers in descending order (10 to 1).

**Challenge 3: Stepping Up**

Can you modify the loop to print only even numbers between 1 and 10 (inclusive)? (Hint: use the modulo operator `%`)


## Day 5: Control Flow - Loops (While Loop)

While loops are another type of loop that continues execution as long as a certain condition is true.

**Challenge 1: Guessing Game**

Write a while loop that generates a random number between 1 and 10 (use `Math.random()`). Allow the user to guess the number using `prompt()`. Keep looping until the user guesses correctly. Print congratulatory messages based on the number of attempts.

**Challenge 2:  Breaking Out**

Imagine a menu system with multiple options (1-3). Use a while loop to keep the menu displayed until the user enters a valid option (1, 2, or 3). Use a `break` statement to exit the loop once a valid option is chosen.

**Challenge 3:  Continuing On**

Let's explore the `continue` statement. Modify the guessing game (Challenge 1) to allow the user to continue playing after a correct guess. Use `continue` to skip to the next iteration of the loop when the guess is correct.


## Day 6: Functions

Functions are reusable blocks of code that perform specific tasks. Today, we'll create our first functions.

**Challenge 1: Greeter Function**

Write a function that takes your name as an argument and prints a greeting message to the console (e.g., "Hello, there [your name]!").

## Day 7: Arrays

Arrays are ordered collections of items that can hold various data types. Let's explore working with arrays.

**Challenge 1:  Creating an Array**

Declare an array to store your favorite movies (at least 3). Print the entire array to the console.

**Challenge 2: Accessing Elements**

Arrays use numerical indexes to access elements. Print the first and last movie titles from your favorite movies array.

**Challenge 3: Modifying the List**

Imagine you want to add a new movie to your favorites list. Use array methods like `push` to add a new element to the end of the array. Print the updated array.


## Day 8: Strings

Strings are sequences of characters used to represent text. Today, we'll explore string manipulation methods.

**Challenge 1:  String Length**

Find the length of your name string (use the `length` property). Print the name and its length to the console.

**Challenge 2:  Extracting a Part**

Imagine you only want the first word of a movie title. Use the `substring` method to extract a portion of a string from your favorite movies array.

**Challenge 3:  Reversing Words**

Can you write a function that takes a string as input and returns the reversed version of the string? (Hint: explore methods like `split` and `join`)


## Day 9: Objects

Objects are collections of key-value pairs used to store data in a structured manner. Today, we'll create objects.

**Challenge 1:  Building a Book Object**

Create an object named `book` with properties like `title` (string), `author` (string), and `year` (number). Assign appropriate values to these properties.

**Challenge 2:  Accessing Object Properties**

Print the title and author of your book object using dot notation (e.g., `book.title`).

**Challenge 3:  Adding More Details**

Let's expand the book object. Add another property named `genre` (string) and assign a genre to the book. Print the entire object to the console using `JSON.stringify`.


## Day 10: DOM Manipulation (Basics)

The Document Object Model (DOM) represents the structure of an HTML document. Today, we'll see a glimpse of DOM manipulation with JavaScript.

**Challenge 1:  Selecting an Element**

Create a simple HTML file with a heading element (h1) containing some text. Use JavaScript to select the heading element by its ID (assign an ID to the h1 element in your HTML).

**Challenge 2:  Changing Content**

Once you've selected the heading element, use JavaScript to modify its content. Try changing the displayed text.

**Challenge 3:  Styling with JavaScript**

While styling is typically done with CSS, JavaScript can also manipulate styles. Try changing the font color or background color of the selected heading element using JavaScript.


## Day 11: Events

Events are user interactions or occurrences within a web page. Today, we'll explore handling events with JavaScript.

**Challenge 1:  Click Event Listener**

Create an HTML button element. Use JavaScript to add a click event listener to the button. When the button is clicked, display an alert message.

**Challenge 2:  Event Object Information**

Within the event listener function from Challenge 1, try accessing the event object. This object contains information about the event, like the type of event (click) or the element that triggered it (the button). Print some properties of the event object to the console.

**Challenge 3:  Multiple Clicks, Different Actions**

Let's modify the button click event listener. Instead of a simple alert, use an if-else statement to display different messages based on the number of times the button has been clicked (keep track of clicks using a variable). 

## Day 12: Forms

HTML forms allow users to submit data. Today, we'll explore how to access form data with JavaScript. 

**Challenge 1:  Grabbing User Input**

Create a simple HTML form with an input field (text type) where users can enter their name. Use JavaScript to access the value entered by the user and print it to the console.

**Challenge 2:  Validation Check**

Before submitting form data, it's often useful to validate user input. Modify the previous challenge to check if the user entered a name. If the name is empty, display an error message using `alert` or modify the form element visually (using styles).

**Challenge 3:  Event Handling with Forms**

Instead of accessing the form data directly, add a submit event listener to the form itself. Within the event listener function, prevent the default form submission behavior and access the form data using the `event.target` property. Print the submitted data to the console.


## Day 13: Higher-Order Functions

Higher-order functions operate on other functions as arguments or return functions as results. Today, we'll explore some common higher-order functions.

**Challenge 1:  Array Manipulation with map**

Create an array of numbers. Use the `map` function to double the value of each element in the array and store the result in a new array. Print both the original and the modified array.

**Challenge 2:  Filtering with filter**

Imagine you only want to keep even numbers from your array of numbers (Day 13, Challenge 1). Use the `filter` function to create a new array containing only the even elements from the original array.

**Challenge 3:  Finding the Sum with reduce**

Calculate the sum of all the elements in your array of numbers (Day 13, Challenge 1). Use the `reduce` function to iterate through the array and accumulate the sum. Print the final sum to the console.


## Day 14: Error Handling (Basics)

Errors are inevitable in programming. Today, we'll learn how to handle errors gracefully using `try...catch` blocks.

**Challenge 1:  Catching a Division by Zero Error**

Write a function that attempts to divide a number by another number entered by the user (using `prompt`). Wrap the division operation in a `try...catch` block. If the user enters zero as the divisor, catch the error and display a user-friendly message using `catch`.

**Challenge 2:  Validating User Input (Again!)**

Modify the form validation challenge from Day 12 (Challenge 2). Instead of using an `alert`, use a `try...catch` block to handle the empty name scenario. Inside the `catch` block, modify the form element visually (using styles) to indicate the error.

**Challenge 3:  Converting Strings to Numbers (Safely)**

Sometimes, you might need to convert user input from a string to a number. However, string input might be invalid. Use a `try...catch` block to wrap the conversion process (using `parseInt` or `parseFloat`). If the conversion fails, catch the error and display an appropriate message.


## Day 15: Asynchronous JavaScript (Intro)

JavaScript is single-threaded, but it can handle asynchronous operations. Today, we'll get a basic understanding of asynchronous concepts.

**Challenge 1:  Simulating Delayed Processing**

Use the `setTimeout` function to simulate a delayed process. Set a timeout of 2 seconds and within the callback function, print a message like "Data processing complete!".

**Challenge 2:  Fetching External Data (Basic Example)**

Imagine you want to display a random quote on your webpage. You can use browser APIs like `fetch` to retrieve data from external sources (APIs). This is a complex topic, but for this challenge, explore basic usage of `fetch` to make a simple request to an example API that provides quotes. You can find free quote APIs online.

**Challenge 3:  Building on Asynchronous Concepts**

Asynchronous operations often involve handling potential errors or delays. Explore how to handle potential errors using `.then` and `.catch` methods when using `fetch` or other asynchronous functions. This provides a more robust way to deal with asynchronous behavior.

**Congratulations!**

You've completed the 15-Day JavaScript Challenge. This is just the beginning of your JavaScript journey. Keep practicing, exploring new concepts, and building your skills!