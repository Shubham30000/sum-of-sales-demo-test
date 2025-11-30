# Sales Summary Demo

## 🚀 Live Demo

Experience the application live: [**Sales Summary Demo**](https://Shubham30000.github.io/sum-of-sales-demo-test/)

## 📋 Overview

This project presents a single-page web application designed to demonstrate dynamic data fetching and processing. It retrieves sales data from an attached `data.csv` file, calculates the total sum of sales, and prominently displays this aggregated value on the page. The application uses Bootstrap 5 for a clean and responsive user interface.

## ✨ Features

*   **Dynamic Data Fetching**: Asynchronously loads sales data from a local CSV file.
*   **Sales Aggregation**: Automatically calculates the sum of the 'sales' column.
*   **Modern UI**: Utilizes Bootstrap 5 for a responsive and aesthetically pleasing design.
*   **Single-Page Application (SPA)**: Delivers a seamless user experience within a single HTML page.
*   **Descriptive Title**: Dynamically sets the page title to 'Sales Summary DEMO'.

## 🛠️ Technologies Used

*   **HTML5**: For structuring the web content.
*   **Bootstrap 5**: A popular CSS framework for responsive design and styling, loaded via jsDelivr CDN.
*   **JavaScript**: For data fetching, parsing, and DOM manipulation to display the sales total.

## 📦 Setup

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Shubham30000/sum-of-sales-demo-test.git
    ```
2.  **Navigate to the project directory**:
    ```bash
    cd sum-of-sales-demo-test
    ```
3.  **Open `index.html` in your browser**:
    Simply open the `index.html` file directly from your file system using any modern web browser. There is no server setup required for this static site.

## 💡 Usage

Upon opening `index.html` in your web browser, the application will automatically perform the following actions:

1.  Fetch the `data.csv` file located in the project's root directory.
2.  Parse the CSV data, specifically extracting values from the 'sales' column.
3.  Calculate the total sum of these sales figures.
4.  Display the computed total inside the `total-sales` element on the page.
5.  The page title will be updated to 'Sales Summary DEMO'.

No user interaction is required to view the sales summary.

## 📁 Project Structure

```
sum-of-sales-demo-test/
├── index.html
└── data.csv
```

*   `index.html`: The main single-page application file, containing the HTML structure, Bootstrap integration, and JavaScript logic for data fetching and display.
*   `data.csv`: The comma-separated values file containing the sales data to be processed.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Shubham30000/sum-of-sales-demo-test/blob/main/LICENSE) file for details.