# Google Sheets Clone Web Application

## Overview
This project is a web application that mimics the core functionalities and user interface of Google Sheets. The application is designed with a focus on providing essential spreadsheet features such as data entry, mathematical and data quality functions, and user-friendly interactions.

---
## Live Demo
[Click here to access the live application](https://your-live-link-here.com)

---
## Screenshots
![Spreadsheet Interface](screenshots/spreadsheet-interface.png)

---
## Features

### 1. Spreadsheet Interface
- **Google Sheets-like UI**: The application closely resembles Google Sheets, including a toolbar, formula bar, and grid structure.
- **Drag Functions**: Supports dragging for cell content, formulas, and selections.
- **Cell Dependencies**: Updates dependent cells dynamically when referenced cells change.
- **Cell Formatting**: Includes options for bold, italics, font size, and color.
- **Row and Column Management**: Users can add, delete, and resize rows and columns.

### 2. Mathematical Functions
The following functions are implemented:
1. **SUM**: Calculates the sum of a range of cells.
2. **AVERAGE**: Calculates the average of a range of cells.
3. **MAX**: Returns the maximum value from a range of cells.
4. **MIN**: Returns the minimum value from a range of cells.
5. **COUNT**: Counts the number of cells containing numerical values in a range.

### 3. Data Quality Functions
The following functions are available:
1. **TRIM**: Removes leading and trailing whitespace from a cell.
2. **UPPER**: Converts text in a cell to uppercase.
3. **LOWER**: Converts text in a cell to lowercase.
4. **REMOVE_DUPLICATES**: Removes duplicate rows from a selected range.
5. **FIND_AND_REPLACE**: Finds and replaces specific text within a range of cells.

### 4. Data Entry and Validation
- Supports data input for numbers, text, and dates.
- Implements basic validation to ensure data integrity (e.g., numeric cells only accept numbers).

### 5. Testing
- Provides a testing mechanism for users to test implemented functions with custom data.
- Displays function execution results clearly.

---

## Bonus Features
- Additional mathematical and data quality functions.
- Complex formula support, including relative and absolute cell references.
- Save and load spreadsheet capabilities.
- Data visualization through charts and graphs.

---

## Tech Stack

### Frontend
- **React**: Used for building the user interface due to its component-based architecture and state management capabilities.
- **Material-UI**: Provides a consistent and modern UI design for components like buttons, dropdowns, and icons.

### Backend
- **Node.js**: Serves API requests and manages business logic.
- **Express.js**: A lightweight framework for routing and middleware.
- **File System**: For saving and loading spreadsheets locally.

### State Management
- **Redux**: Manages application state and facilitates data flow between components.

### Testing
- **Jest**: Unit testing for functions and components.
- **React Testing Library**: Ensures user interactions are correctly implemented.

---

## Data Structures
- **Grid Representation**: A two-dimensional array is used to represent the spreadsheet grid. Each cell is an object with properties like `value`, `formula`, `dependencies`, `style`, etc.
- **Dependency Graph**: A directed graph structure is used to manage cell dependencies, ensuring efficient updates when cells change.
- **Clipboard**: Stores cell data temporarily for copy, cut, and paste operations.

---

## Installation and Usage

### Clone the Repository
```bash
git clone https://github.com/Tirthraj1605/Google-Sheets-Clone.git
cd Google-Sheets-Clone
