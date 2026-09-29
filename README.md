# Scientific Calculator

A desktop-based **Scientific Calculator** built using **Java and JavaFX**. The graphical user interface was designed using **Scene Builder and FXML**, while the calculator operations and interaction logic were implemented in Java.

## Features

### Basic Operations

* Addition
* Subtraction
* Multiplication
* Division
* Power (`x^y`)
* Percentage
* Decimal input

### Scientific Operations

* Sine (`sin`)
* Cosine (`cos`)
* Tangent (`tan`)
* Inverse sine (`sin⁻¹`)
* Inverse cosine (`cos⁻¹`)
* Inverse tangent (`tan⁻¹`)
* Hyperbolic sine (`sinh`)
* Hyperbolic cosine (`cosh`)
* Hyperbolic tangent (`tanh`)
* Natural logarithm (`log`)
* Exponential (`e^x`)
* Square (`x²`)
* Cube (`x³`)
* Cube root
* Factorial

### Calculator Controls

* **AC** — Clears the entire display
* **C** — Removes the last entered character
* **OFF** — Closes the application
* Decimal-point validation prevents multiple decimal points from being entered

## What I Learned

This project gave me hands-on experience in building a desktop GUI application and connecting user interactions with Java programming logic.

### Java Programming

* Working with Java classes and methods
* Using variables and different data types
* Converting strings to numerical values using `Double.parseDouble()`
* String manipulation using methods such as `substring()` and `contains()`
* Using conditional statements
* Using `for` and `while` loops
* Working with Java's `Math` class
* Implementing factorial and power calculations using loops
* Converting inverse trigonometric results from radians to degrees

### JavaFX & GUI Development

* Building a desktop application using JavaFX
* Working with `Stage`, `Scene`, and `FXMLLoader`
* Using JavaFX controls such as `Button`, `TextField`, and `Label`
* Handling button clicks using `ActionEvent`
* Connecting FXML components to Java using `@FXML`
* Using `event.getSource()` to identify which button was pressed
* Reading and updating the calculator display dynamically
* Connecting the GUI with the underlying Java logic

### FXML & Scene Builder

* Designing the graphical user interface using **Scene Builder**
* Creating and working with FXML layouts
* Connecting FXML controls to controller methods
* Using `fx:id` and `@FXML` for controller interaction
* Separating the user interface from the application logic

## How the Calculator Works

The calculator keeps track of the first number and the selected operator before accepting the second number.

The basic calculation flow is:

```text
First number
     ↓
Select operator
     ↓
Second number
     ↓
Press =
     ↓
Perform calculation
     ↓
Display result
```

For scientific operations, the value currently shown on the display is passed to the corresponding mathematical function.

For example, trigonometric calculations use Java's built-in `Math` functions, while operations such as factorial and power were implemented using loops.

## Project Structure

```text
src/
└── uicalculator/
    ├── UICALCULATOR.java
    ├── FXMLDocumentController.java
    └── FXMLDocument.fxml
```

* **`UICALCULATOR.java`** — Starts the JavaFX application, loads the FXML file, creates the scene, and displays the window.
* **`FXMLDocumentController.java`** — Contains the calculator's interaction and mathematical logic.
* **`FXMLDocument.fxml`** — Defines the graphical user interface designed with Scene Builder.

## Technical Highlights

* Event-driven programming with JavaFX
* FXML-based GUI design
* Scene Builder for visual interface development
* JavaFX event handling using `ActionEvent`
* Connecting UI elements with controller methods using `@FXML`
* Dynamic display handling using `TextField`
* Arithmetic and scientific calculations
* Loop-based factorial and power calculations
* String-based numerical input handling
* Basic input validation
* Inverse trigonometric calculations with degree conversion
* Basic division-by-zero handling

## Tech Stack

* Java
* JavaFX
* FXML
* Scene Builder
* NetBeans

