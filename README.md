# Population-Retriever
Population Lookup Program (Python)

This project is a simple command-line program built using Python. The application allows users to enter a state code and retrieves the corresponding population from a predefined dataset.

Overview:
The application demonstrates basic input handling, dictionary usage, functions, and loops in Python. When run, the program prompts the user to enter a state code, validates the input, and displays the population if the code is valid. Invalid inputs are handled gracefully, and the user can choose to try again or exit the program.

Features:

Retrieve population data based on state codes

Validates user input and handles unrecognized codes

Allows the user to try again or terminate the program

How the Program Works:

Input Handling:
The user is prompted to enter a state code. Input is standardized to uppercase to match the keys in the dataset.

Data Retrieval:

The program uses a function to look up the population in the dataset dictionary

If the code exists, the population is returned and displayed

If the code does not exist, an error message is shown, and the user can choose to try again

Button Functions:

Not applicable (command-line interface)

Requirements:

Python 3.x

How to Run:
Run the program from a terminal or command prompt using:
python population_lookup.py
