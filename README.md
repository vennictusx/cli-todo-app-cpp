CLI Todo List Application
This is a simple, command-line interface (CLI) to-do list application written in C++. It allows a user to manage a list of tasks, track their progress, and mark them as complete.

Features
Add Tasks: Easily add new tasks with a unique, sequential ID.

Mark as Completed: Mark tasks as complete by entering their ID.

Track Progress: Update the progress of any task with a percentage (0-100%).

Clear All Tasks: Wipe the entire list clean.

Sorted Display: Tasks are automatically sorted and displayed with incomplete tasks first, followed by completed tasks.

Progress Bar: Visual progress bars are displayed for each task, showing its completion percentage.

How to Build and Run
To compile and run this application, you will need a C++ compiler (like g++).

Save the code: Save the C++ code in a file named todo.cpp.

Compile: Open your terminal and run the following command to compile the code:

g++ todo.cpp -o todo

Note: The windows.h header file is specific to Windows. If you are on a different operating system, you may need to remove that line and any code that uses it (e.g., Sleep(), system("cls")).

Run: Execute the compiled program with the following command:

./todo

Usage
When you run the application, you will be presented with a simple menu:

[A]dd Item: Adds a new task to your list.

[M]ark Item as Completed: Marks an existing task as 100% complete.

[P]rogress Item: Allows you to set a percentage of completion for a task.

[C]lear Memory: Deletes all tasks from the list.

[E]xit: Closes the application.

Technologies Used
C++: The core language used to build the application.

Standard Library: Utilizes standard C++ libraries for basic I/O and data structures (iostream, string, list).
