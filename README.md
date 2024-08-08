# Is X in Y?

## Project Information
This project contains a Python application with a graphical user interface (GUI) built with PyQt5, designed to perform certain operations on Excel files.

The project is mainly composed of two classes, Gui and Compare.

## Dependencies:
- Python 3.9.12
- Openpyxl, Pandas and PyQt5 libraries

## Gui Class
The `Gui` class constructs the graphical user interface components.

Instance attributes of this class include various elements of the UI such as labels (`titleLabel`, `inTitleLabel`, `outTitleLabel`, `inPathLabel`, `isPathLabel`, `inColLabel`, `isColLabel`), inputs (`inPathInput`, `isPathInput`, `outPathInput`), selection buttons (`inPathButton`, `isPathButton`, `outButton`), and others (See the code for a comprehensive list). 

It also defines the following methods:

- `__init__`: This method initializes the GUI window with the specified dimensions.
- `initUI`: This method sets up the layout and user interface elements.
- `select_file`: This method is used to select an Excel file and read it into a pandas DataFrame.
- `select_out_path`: This method enables user to specify an output path for Excel files.
- `confirm`: This method gathers inputs from the user and proceeds to the comparison process.

## Compare Class
The `Compare` class is used to compare values from two Excel files.

This class contains the `execute` method which executes comparison and writes results back to an Excel file.

For more detailed information about the specific functions, methods, and variables, refer to the source code and the included comments.

## Usage
This project can be executed by running the main Python script. The user can interact with the graphical user interface to input the necessary information for the application to process.

## Note
This documentation is a simplification of the project details. For more technical and comprehensive details, please refer to comments and docstrings within the source code.