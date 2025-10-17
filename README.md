# Sales Summary Web App

This is a simple, single-page web application designed to fetch sales data from a `data.csv` file, calculate the total sales from its 'sales' column, and display it prominently on a responsive web page. The site title is dynamically updated with a unique 'seed' upon loading.

## Project Structure

```
.
├── index.html
├── data.csv
├── README.md
└── LICENSE
```

## How to Run

1.  **Save the files:**
    *   Save the content of `index.html` into a file named `index.html`.
    *   Save the content of `data.csv` (an example is provided below) into a file named `data.csv` in the **same directory** as `index.html`.
    *   Save the content of `LICENSE` into a file named `LICENSE`.
    *   Save the content of `README.md` into a file named `README.md`.

2.  **Open `index.html`:** Simply open the `index.html` file in your web browser.

The application will automatically fetch `data.csv`, calculate the total sales from the 'sales' column, and display the sum.

## Features

*   **Single-file application:** All HTML, CSS (via Tailwind CDN), and JavaScript are contained within `index.html`.
*   **Responsive design:** Built with Tailwind CSS for optimal viewing on various screen sizes.
*   **Dynamic Title:** The page title updates to "Sales Summary {seed}" where {seed} is a random number.
*   **Data Fetching:** Fetches `data.csv` from the same directory and processes it.

## `data.csv` Format

The `data.csv` file is expected to have a header row, and at least one column named `sales`. The values in the `sales` column should be numerical. Example:

```csv
product,sales,region
Widget A,1200.50,North
Gadget B,850.75,South
Doodad C,2100.00,East
Thingamajig D,450.25,West
Example E,150.00,North
```

## Error Handling

The application includes basic error handling for issues like `data.csv` not being found, being empty, or missing the 'sales' column. Errors will be displayed on the page.