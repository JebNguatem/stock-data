# Stock Data Repository

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/JebNguatem/stock-data.git
   cd stock-data
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage Examples

### stock_data_downloader.py
To download stock data, run:
```bash
python stock_data_downloader.py --symbol AAPL --start 2020-01-01 --end 2021-01-01
```
- **Parameters**:
  - `--symbol`: The stock ticker symbol (e.g., AAPL for Apple).
  - `--start`: The start date for the data download (format: YYYY-MM-DD).
  - `--end`: The end date for the data download (format: YYYY-MM-DD).

### visualize_stock_data.py
To visualize stock data, run:
```bash
python visualize_stock_data.py --file stock_data.csv
```
- **Parameters**:
  - `--file`: The CSV file containing the stock data.

## Visualization Features Documentation
- The visualizations include:
  - Line charts showing stock price trends over time.
  - Bar charts representing volume of stocks traded.
  - Customizable plots with various options for styling and formatting.

Feel free to contribute to the code or submit issues for any bugs or feature requests!