# AirBnB Clone Project

<!-- ![AirBnB Logo](https://camo.githubusercontent.com/a0c52a69dc410e983b8c63fa4aa57e83cb4157cd/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f696e7472616e65742d70726f6a656374732d66696c65732f686f6c626572746f6e7363686f6f6c2d6869676865722d6c6576656c5f70726f6772616d6d696e672b2f3236332f4842544e2d68626e622d46696e616c2e706e67) -->

## Description

This project is a simplified clone of the AirBnB website. It primarily focuses on developing a command-line interface (CLI) to manage the program in a shell environment. The CLI will allow users to create, retrieve, update, and destroy objects, as well as manage file storage.

## Command Interpreter

The command interpreter is the core of this project, providing a shell-like interface to interact with the AirBnB clone system.

### How to Start the Interpreter

To start the command interpreter, run the following command in your terminal:

```bash
./console.py
```

### How to Use the Interpreter

Once the interpreter is running, you can use various commands to manage the AirBnB objects. Here are some example commands:

```
(hbnb) create User
(hbnb) show User 1234-5678-9012
(hbnb) update User 1234-5678-9012 email "user@example.com"
(hbnb) destroy User 1234-5678-9012
(hbnb) all
(hbnb) quit
```

### Available Commands

- `create`: Create a new object
- `show`: Display information about an object
- `update`: Update an object's attributes
- `destroy`: Remove an object
- `all`: List all objects or all objects of a specific class
- `quit` or `EOF`: Exit the program

## Installation

To get started with the AirBnB clone project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/alu-AirBnB_clone.git
   ```

2. Navigate to the project directory:
   ```bash
   cd alu-AirBnB_clone
   ```

3. Make the console script executable:
   ```bash
   chmod +x console.py
   ```

## Testing

To run all the tests for the project, execute the following command:

```bash
python3 -m unittest discover tests
```

To run a specific test file, use:

```bash
python3 -m unittest tests/test_models/test_city.py
```

## Authors

- [Your Name]
- [Collaborator's Name]

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
