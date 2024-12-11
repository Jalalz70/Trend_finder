# Stock Trend Analyzer

A simple Python program to analyze stock trends. The program takes a list of stocks from the user and analyzes the last two peaks and valleys of each stock. If the last two peaks and the last two valleys are higher, the stock is considered to be in an uptrend. Conversely, if the last two peaks and the last two valleys are lower, the stock is considered to be in a downtrend. Finally, the program returns two lists indicating the stocks in an uptrend and those in a downtrend.

## Inputs
- `fractal_scale`: The scale of peaks and valleys to be found.
- `symbols`: The list of stocks entered by the user.
- `get_new_data`: Whether to fetch new data.
- `show_chart`: Whether to display the chart for each stock.

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/Jalalz70/Trend_finder.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Trend_finder
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Run the program:
    ```sh
    python main.py
    ```
2. Follow the prompts to enter the `fractal_scale`, `symbols`, and preferences for `get_new_data` and `show_chart`.

## Output
- The program will output two lists:
    - **Uptrend Stocks**: Stocks that are considered to be in an uptrend.
    - **Downtrend Stocks**: Stocks that are considered to be in a downtrend.


