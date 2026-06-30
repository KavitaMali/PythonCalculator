# Python Calculator 🧮

A simple command-line calculator built using Python that performs basic arithmetic operations and stores calculation history.

## Features

✔ Perform basic mathematical operations:

* Addition (`+`)
* Subtraction (`-`)
* Multiplication (`*`)
* Division (`/`)

✔ Calculation History

* Stores and displays the last **5 calculations**

✔ Error Handling

* Prevents division by zero
* Handles invalid operations

✔ Simple Menu Interface

* Easy-to-use command line interaction

---

## Project Structure

```text
calculator.py
README.md
```

---

## Requirements

* Python 3.x

Check Python version:

```bash
python --version
```

---

## How to Run

1. Clone or download the project.

2. Open terminal or command prompt.

3. Navigate to the project folder.

4. Run:

```bash
python calculator.py
```

---

## Menu Options

```text
Options:
c → Calculate
h → View History
q → Quit
```

---

## Example Usage

```text
---------------------------------------------
               Python Calculator
---------------------------------------------

Options: c for calculate, h for history, q for quit

choose: c

Enter first number: 10
choose operation +,-,*,/: *
Enter second number: 5

50
```

View history:

```text
choose: h

10*5=50
20+10=30
100/2=50
```

---

## Functions Used

### `calculate(a, op, b)`

Performs the selected arithmetic operation.

Parameters:

* `a` → First number
* `op` → Operator (`+`, `-`, `*`, `/`)
* `b` → Second number

Returns:

* Calculation result

Raises:

* `ZeroDivisionError`
* `ValueError`

### `main()`

Handles:

* User interaction
* Menu display
* History management

---

## Current Limitations

* Accepts only integer inputs
* Supports only `+`, `-`, `*`, `/`
* Advanced operations (`%`, `**`, `√`) are not implemented yet
* History exists only during runtime (not saved permanently)

---

## Future Improvements

* Add modulus (`%`)
* Add power (`**`)
* Add square root (`√`)
* Save history to file
* Improve input validation
* Support decimal numbers

---

## Author

Created as a Python practice project.
