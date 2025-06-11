#  Global Stock Index Analysis

This project uses historical stock index data from Yahoo Finance to explore trends, behaviors, and insights across global financial markets. Using Python and Jupyter Notebook, we load, clean, analyze, and visualize decades of financial index data.

---

##  About the Dataset

This dataset encompasses the **historical data of major stock indices** from around the world, sourced directly from [Yahoo Finance](https://finance.yahoo.com/). With data reaching back to the **1920s** where available, it offers a rich repository for:

---

##  File Description

### `all_indices_data.csv`

A consolidated dataset combining multiple global indices, containing the following columns:

| Column   | Description                                                                 |
|----------|-----------------------------------------------------------------------------|
| `date`   | Date of the observation (YYYY-MM-DD)                                        |
| `open`   | Opening price of the index                                                  |
| `high`   | Highest price reached during the trading day                                |
| `low`    | Lowest price reached during the trading day                                 |
| `close`  | Closing price of the index                                                  |
| `volume` | Trading volume (some indices may have missing or zero volume)               |
| `ticker` | Ticker symbol of the stock index (e.g., `^GSPC`, `^N225`, `^VIX`, etc.)     |

---

##  Analysis Performed

-  Data cleaning: Checked for missing, duplicate, and zero-volume records  
-  Date parsing: Extracted month, year, and weekday to explore patterns  
-  Price change analysis: Investigated price changes on low vs. active trading days  
-  Visualizations: Line plots, distribution charts, weekday trends, etc.  
-  Insights: Uncovered behavioral differences across indices and trading days  

---
