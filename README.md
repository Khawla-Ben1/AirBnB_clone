# AirBnB_clone
Airbnb Console Command-Line Interface (CLI)

This project implements a command-line interface (CLI) for managing Airbnb-like data. It provides functionalities to interact with data models such as users, places, reviews, and amenities.
Command Interpreter

The command interpreter allows users to interact with the Airbnb data through a command-line interface. Below are the instructions on how to start and use the command interpreter.
Starting the Command Interpreter

To start the command interpreter :
--------------------------------
 - Clone the repository to your local machine.
 - Navigate to the directory containing the cloned repository.
 - Run the command ./console.py to start the command interpreter.

Using the Command Interpreter :
-------------------------------

Once the command interpreter is started, you can use various commands to manage Airbnb data. Here are some available commands and their usage:

    - help: Displays a list of available commands and their usage.
    - create <model_name>: Creates a new instance of the specified model.
    - show <model_name> <id>: Displays details of the instance with the specified ID.
    - destroy <model_name> <id>: Deletes the instance with the specified ID.
    - all <optional_model_name>: Displays all instances of the specified model, or all models if no model name is provided.
    - update <model_name> <id> <attribute_name> "<new_value>": Updates the specified attribute of the instance with the given ID.
    - quit or EOF: Exits the command interpreter.

Examples
--------
    *To create a new user:
        (cmd) create User

    *To display all places:
        (cmd) all Place

    *To update the description of a place:
     (cmd) update Place 12345 description "New description"
