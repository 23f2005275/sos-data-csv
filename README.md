# Sales Dashboard

A responsive single-page application built with HTML, Tailwind CSS, and JavaScript to visualize sales data from a `data.csv` file.

## Features

*   **CSV Data Loading**: Fetches and parses sales data from a `data.csv` file in the same directory.
*   **Comprehensive Data Display**: Shows all transaction data in a well-structured, scrollable table.
*   **Sales Summary**: Provides key metrics like total sales and the number of transactions.
*   **Theme Toggle**: Easily switch between light and dark modes with a button in the navigation bar. Your theme preference is saved in local storage.
*   **Responsive Design**: Adapts seamlessly to various screen sizes, from mobile devices to large desktops, thanks to Tailwind CSS.
*   **Error Handling**: Displays user-friendly error messages if the `data.csv` file cannot be loaded or is malformed.

## Setup

To run this project, simply download all files and open `index.html` in your web browser. No complex server setup or build process is required.

### Data Requirements

Ensure you have a `data.csv` file in the same directory as `index.html`. The CSV file should have a header row, and ideally, include a column named `sales` (case-insensitive) for the total sales calculation. Other columns will be displayed as-is.

Example `data.csv` format:

```csv
ID,Product,Category,Sales,Date
1,Laptop,Electronics,1200.50,2023-01-15
2,Mouse,Electronics,25.99,2023-01-15
3,Keyboard,Electronics,75.00,2023-01-16
4,Book,Books,15.75,2023-01-16
```

## Technologies Used

*   **HTML5**: For the basic structure of the web page.
*   **Tailwind CSS**: For utility-first styling and responsive design.
*   **JavaScript (ES6+)**: For fetching, parsing, and displaying data, as well as handling the theme toggle functionality.

## Usage

1.  Place your `data.csv` file in the same directory as `index.html`.
2.  Open `index.html` in your preferred web browser.
3.  The dashboard will automatically load and display the sales data.
4.  Use the "Toggle Theme" button in the navigation bar to switch between light and dark modes.