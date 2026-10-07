# Area Calculator Using Python

A simple command-line Python program that calculates the area of common 2D shapes and the total surface area of selected 3D shapes.

## Features

The calculator supports:

- Circle
- Rectangle
- Square
- Triangle
- Trapezoid
- Cube
- Cuboid
- Sphere

The program uses a menu-driven interface and continues running until the user chooses **Exit**.

## Requirements

- Python 3.x
- No external packages are required.

The program uses Python's built-in `math` module for `math.pi`.

## How to Run

1. Save the Python code as `area_calculator.py`.
2. Open a terminal or command prompt in the folder containing the file.
3. Run:

```bash
python area_calculator.py
```

If your system uses `python3`, run:

```bash
python3 area_calculator.py
```

## How to Use

When the program starts, it displays:

```text
--- Area Calculator ---
1. Circle
2. Rectangle
3. Square
4. Triangle
5. Trapezoid
6. Cube
7. Cuboid
8. Sphere
9. Exit
```

Enter the number of the shape you want to calculate.

For example, selecting `1` asks for the radius:

```text
Enter your shape number: 1
Radius: 5
Area = 78.53981633974483
```

To close the program, select option `9`.

## Formulas

| Shape | Formula |
|---|---|
| Circle | π × r² |
| Rectangle | length × breadth |
| Square | side² |
| Triangle | ½ × base × height |
| Trapezoid | ½ × (a + b) × height |
| Cube | 6 × side² |
| Cuboid | 2(lb + bh + hl) |
| Sphere | 4 × π × r² |

## Project Structure

```text
Area Calculator Project/
│
├── area_calculator.py
├── README.md
└── PROJECT_STATEMENT.md
```

## Python Concepts Demonstrated

- Importing modules with `import`
- Functions using `def`
- Returning values with `return`
- Variables
- `input()` and `float()`
- Arithmetic operators
- `if`, `elif`, and `else`
- `while` loop
- `break`
- `math.pi`

## Notes

- The program is text-based and runs in the command line.
- The user should enter valid numerical values for dimensions.
- Units are not automatically handled or converted, so dimensions should be kept consistent.
