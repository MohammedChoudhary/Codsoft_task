# Problem Statement of Tasks

## To-Do List-Description:

This is a simple command-line to-do list code implemented in Python. The code allows users to add tasks, view all tasks, and mark tasks as done. It runs in a loop until the user decides to exit.

**Code Explanation:**
```text
tasks: A list that holds tasks, where each task is a dictionary containing a task description and its completion status.
Main Menu: The user interacts with the application via a menu with options to add tasks, show tasks, mark tasks as done, or exit.
Add Task: Users can add multiple tasks at once. Each task is stored with its description and a done status initially set to False.
Show Tasks: Displays all tasks with their statuses (Done or Not Done).
Mark Task as Done: Users can mark a specific task as done based on its number.
Exit: Ends the program.
what did I learn?:
I learned how to manage a list of tasks using dictionaries, handle user inputs, and implement basic menu-driven program logic.
```

## Calculator-Description:

This is a basic calculator code that performs simple arithmetic operations. Users input two numbers and an operator, and the program outputs the result of the operation.

**Code Explanation:**
```text
User Input: Collects two numbers and an operator from the user.
Operations: Performs the operation based on the user’s choice (+, -, *, /, %, //).
Addition (+): Adds two numbers.
Subtraction (-): Subtracts the second number from the first.
Multiplication (*): Multiplies the two numbers.
Division (/): Divides the first number by the second.
Modulus (%): Finds the remainder when the first number is divided by the second.
Integer Division (//): Performs integer division.
Error Handling: Provides an error message if an invalid operator is entered.
```

## Password Generator-Description:

This code generates a random password based on some user preferences. For instance, the user may want to input the minimum size of the password and if numbers and special characters will be included in it.

Libraries Used:

random: Helps in generating characters that are random.

string: Gives you a string constant from various things (letters, digits, punctuation).

**Code Explanation:**
```text
Character Sets: Use of string.ascii_letters, string.digits and string.punctuation has been done to build sets of characters.

Password Generation: Here is done by randomly picking characters form the pool until it reaches the lower limit defined as well as other conditions(if there are any).

Criteria Checking: This is where it checks whether your generated password has at least one number or special character according to your options chosen during generation.

Learn:

learned about random, string manipulation, and how to ensure that generated passwords meet certain criteria.
```

## 4-Rock-Paper-Scissors Game-Description:

Rock-Paper-Scissors is a minimalist command-line game of RPS that pits the user against the computer. The game counts scores from round to round and then declares the overall winner.

Libraries Used:

random: For random selection of options for computer.

**Code Explanation:**
```text
Game Loop: Plays a set number of rounds (5 by default) or it stops when player opts out.

User Input: A number entered by the player determines whether they chose rock, paper or scissors.

Computer Choice: Randomly picks option selected by a computer.

Result Evaluation: Award points based on standard rules in rock-paper-scissors.

Score Tracking: It keeps a record of players’ scores and displays the final outcome of the game.

Learning Reflection:

You practiced implementing game logic, managing scores, and handling user inputs.
```

## 5-The Contact Book

Summary:

A contact book that can be used through the command line for adding, searching, and displaying contacts, updating them or deleting some of them. That’s why it uses tabulate library to format for our contact display.

Libraries Employed:

tabulate: It is employed in order to arrange contacts within a grid form.

Comments for Code:

Contact Storage: The details of phone number, email and address are stored as a dictionary and labeled as Contacts.

Menu Options: These are what enable users to perform various actions like adding new entries, updating existing ones or removing those that became irrelevant.

Display Function: With the help of tabulate library we can see a beautiful table with all our contacts in it.

CRUD Operations: This is an abbreviation standing for Create,Read, Update and Delete operations that are vital when it comes to contact management.

Lessons Learned:

This helped me to learn how to leverage external libraries to improve functionality; manage your data structures more effectively while maintaining their integrity and handle user inputs related to CRUD operations.