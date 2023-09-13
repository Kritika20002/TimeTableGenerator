# Time Table Generator

This is a simple dart Project for time table generation. The Project take the user input for the day, the number of tasks she wants to insert and the specific tasks. Once the user is done inserting, she can type in 'PRINT' for the program to display the generated time table.

## Usage

1. Clone or download this repository to your local machine.

2. Make sure you have Dart installed. You can download and install it from the Dart website.

3. Open a terminal and navigate to the directory where you have the timetablegenerator.dart file.

4. Run the program using the following command:
```agsl
dart timetablegenerator.dart
```

5. The program will start and prompt you to enter the days, the number of tasks for a particular day and your tasks for those days. Follow the instructions provided by the program.

6. When you are done entering your tasks, simply type "PRINT" to generate and display the time table.

## Example

Below is an example of how the program runs:

```agsl
Welcome to Time Table Generator!
Please enter the days and your particular plan for them, and I'll generate the time table for you.
Write PRINT to get it generated.

Please enter the day- MONDAY
Please enter the number of tasks you want to insert- 2
Enter Task 1
Study
Enter Task 2
Gym

Please enter the day- TUESDAY
Please enter the number of tasks you want to insert- 3
Enter Task 1
Work
Enter Task 2
Lunch
Enter Task 3
Meeting

Please enter the day- WEDNESDAY
Please enter the number of tasks you want to insert- 1
Enter Task 1
Run

Please enter the day- TUESDAY
Please Enter a day for which you haven't assigned tasks yet

Please enter the day- PRINT
Generating time table...
--------------------------------
MONDAY    | Study | Gym | n | n | n | n | n |
--------------------------------
TUESDAY   | Work | Lunch | Meeting | n | n | n | n |
--------------------------------
WEDNESDAY | Run | n | n | n | n | n | n |
--------------------------------
THURSDAY  | n | n | n | n | n | n | n |
--------------------------------
FRIDAY    | n | n | n | n | n | n | n |
--------------------------------
SATURDAY  | n | n | n | n | n | n | n |
--------------------------------
SUNDAY    | n | n | n | n | n | n | n |
--------------------------------

```