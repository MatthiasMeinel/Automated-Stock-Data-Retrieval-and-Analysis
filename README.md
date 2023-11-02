# Automated-Stock-Data-Retrieval-and-Analysis

# Stock Data Automation

In this project, we aim to automate the process of gathering stock data. To achieve this, we utilize the `selenium` library for web scraping.

## Objective
To automate the process of fetching stock data, clean it, and then apply filters to select specific stocks based on set criteria.

## Libraries Used
- pandas
- numpy
- selenium
- webdriver_manager

## Data Source
We are scraping stock data from [Fundamentus](https://fundamentus.com.br/resultado.php).

## Implementation
1. Initialize the Chrome driver.
2. Navigate to the Fundamentus website.
3. Locate the stock data table using its XPath.
4. Extract the HTML content of the table.
5. Convert the HTML table into a pandas DataFrame.
6. Clean the data (e.g., handle Brazilian decimal format).
7. Apply filters to select specific stocks.
8. Rank stocks based on certain criteria.

## Steps to Run
1. Ensure you have all the required libraries installed.
2. Clone the repository.
3. Run the Python script.

## Results
The script outputs a DataFrame of stocks ranked based on the `EV/EBIT` and `ROIC` criteria.

## Note
When using this script, be aware of potential website structure changes that could break the scraping process. Ensure you have permissions to scrape the website.

## Contribution
Feel free to fork this repository and make enhancements.

