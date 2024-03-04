# Stock Data Extraction and Visualization

This Jupyter notebook contains a project that focuses on extracting and visualizing stock data for Tesla (TSLA) and GameStop (GME). The project uses the `yfinance` library to extract stock data, `BeautifulSoup` for web scraping revenue data, and `plotly` for data visualization.

## Project Structure

The project is divided into several sections:

1. **Extracting Stock Data**: This section uses the `yfinance` library to extract stock data for Tesla and GameStop. The data is stored in pandas DataFrames.

2. **Web Scraping for Revenue Data**: This section uses `requests` and `BeautifulSoup` to scrape revenue data for Tesla and GameStop from specific webpages. The scraped data is cleaned and stored in pandas DataFrames.

3. **Data Visualization**: This section uses the `plotly` library to create interactive plots of the stock data and revenue data. The `make_graph` function is defined to create subplots of historical share price and historical revenue for a given stock.

## Running the Notebook

To run the notebook, you will need to install the required libraries. You can do this by running the following command:

```python
!pip install yfinance beautifulsoup4 plotly pandas
```

After installing the necessary libraries, you can run the notebook cell by cell to see the extraction, cleaning, and visualization processes in action.

## Note

The data used in this project is up to date as of June 2021. For the most accurate and current results, you may need to update the data extraction sections with more recent URLs or use a different method to obtain the most recent stock and revenue data.
