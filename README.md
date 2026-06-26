# Multi Utility Toolkit

## Project Overview

The **Multi Utility Toolkit** is a Python-based console application designed using Python modules, packages, and built-in libraries. This project demonstrates modular programming using built-in modules and custom modules to perform various utility operations such as date-time processing, mathematical calculations, random data generation, UUID creation, file handling, and module exploration.

The toolkit uses a menu-driven interface allowing users to interact with different functionalities efficiently.

---

## Features

### 1. Date and Time Operations

Uses Python's `datetime` and `time` modules to:

* Display current date and time
* Calculate difference between dates
* Format date and time
* Implement stopwatch functionality

---

### 2. Mathematical Operations

Uses Python's `math` module to:

* Calculate square root
* Calculate factorial
* Perform trigonometric calculations
* Calculate compound interest
* Find area of geometric shapes

---

### 3. Random Data Generation

Uses Python's `random` module to:

* Generate random numbers
* Generate random passwords
* Generate OTPs
* Randomly sample data from lists

---

### 4. Unique Identifier Generation

Uses Python's `uuid` module to:

* Generate unique IDs
* Create UUID4 identifiers for records or files

---

### 5. File Operations (Custom Module)

Provides file handling functionality:

* Create files
* Write data into files
* Read file content
* Append data to files

---

### 6. Module Exploration

Uses `dir()` function to:

* Explore built-in module attributes
* Dynamically inspect modules

---

### 7. Exit Program

* Safely exits the toolkit

---

## Project Structure

```text
Modular & Packager/
│
├── main.py
│
└── Packages/
    ├── __init__.py
    ├── file_utils.py
    └── math_utils.py
```

---

## Concepts Demonstrated

### Built-in Modules

The project uses:

* datetime
* time
* math
* random
* uuid

---

### Custom Modules

Custom modules created:

* file_utils.py
* math_utils.py

---

### Packages

Package implementation using:

```python
__init__.py
```

---

### User Defined Functions (UDF)

Functions created:

* date_time()
* stopwatch()
* math_operations()
* random_operations()
* generate_uuid()
* file_menu()
* explore()
* menu()

---

### Dynamic Module Exploration

Used in:

```python
dir(math)
dir(random)
```

---

### Main Function Execution

Uses:

```python
if __name__=="__main__":
    menu()
```

This ensures that the program executes only when run directly.

---

## Program Flow

1. User starts the program.
2. Main menu is displayed.
3. User selects an option.
4. Program performs the requested operation.
5. Results are displayed.
6. User may continue using the toolkit.
7. User exits the program safely.

---

## Output Screenshots

### Main Menu

![Main Menu](mainmenu.png)

### Date and Time Operations

![Datetime](datetime.png)

### Mathematical Operations

![Math](math.png)

### Random Data Generation

![Random](random.png)

### UUID Generation

![UUID](uuid.png)

### File Operations

![Files](files.png)

### Module Exploration

![Module](module.png)

---

## Project Demo Video

Watch the complete project demonstration here:

[▶ Watch Demo Video](Paste_Google_Drive_Link_Here)

---

## Author

**Sarth Thakar**
