# Sales Summary DEMO

## Live Demo
Check out the live application here: [DEPLOYMENT_URL_PLACEHOLDER](DEPLOYMENT_URL_PLACEHOLDER)

## Overview
This project presents a simple, single-page web application designed to fetch sales data from a local `data.csv` file, process it, and display the total sales sum. It's built with modern web technologies, offering a clean and responsive user interface.

## Features
*   **Dynamic Data Fetching**: Fetches sales data directly from `data.csv`.
*   **Sales Calculation**: Automatically parses the CSV and calculates the sum of the 'sales' column.
*   **Responsive Design**: Utilizes Bootstrap 5 for a responsive and mobile-friendly layout.
*   **Loading Indicator**: Provides a visual loading spinner while data is being processed.
*   **Error Handling**: Displays an error message if data fetching or processing fails.

## Technologies Used
*   **HTML5**: Structure of the web page.
*   **CSS3**: Custom styles for the application.
*   **JavaScript**: For fetching, parsing, and manipulating data.
*   **Bootstrap 5**: CSS framework for responsive design and UI components.

## Setup
To run this project locally, follow these steps:

1.  **Ensure `data.csv` is in the same directory** as `index.html`. The application expects `data.csv` to be present in the root.

2.  **Open `index.html`** in your web browser. You can simply drag and drop the `index.html` file into your browser or right-click and choose "Open with Browser".

## Usage
Once `index.html` is opened in your browser, the application will automatically:
1.  Attempt to fetch `data.csv`.
2.  Parse the CSV content.
3.  Sum the values in the 'sales' column.
4.  Display the total sales amount in the designated area.

If `data.csv` is not found, or if the 'sales' column is missing, an error message will be displayed.

## Project Structure
```
.
├── index.html
├── data.csv
└── README.md
└── LICENSE
```
*   `index.html`: The main single-page application.
*   `data.csv`: The sales data in CSV format, expected to contain a 'sales' column.
*   `README.md`: This project documentation.
*   `LICENSE`: The MIT License for this project.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.