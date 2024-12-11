# Pool Analysis Project

This project analyzes various pools and ranks them based on different metrics such as TVL (Total Value Locked), APY (Annual Percentage Yield), and SoDeFi Score. The analysis is performed on stablecoin pools and the results are saved in CSV and PNG formats.

## Project Structure

- `P_Analysis_stable.py`: Main script for analyzing the pools and generating the rankings.
- `League_Standings/`: Directory where the output CSV and PNG files are saved.

## Requirements

- Python 3.x
- pandas
- great_tables

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/RazDwa1923/Pool_Analysis.git
    cd Pool_Analysis
    ```

2. Install the required packages:
    ```bash
    pip install pandas great_tables
    ```

## Usage

1. Run the main analysis script:
    ```bash
    python P_Analysis_stable.py
    ```

2. The script will generate the following files:
    - `League_Standings/top10_league_stable.csv`: CSV file containing the top 10 stablecoin pools ranked by SoDeFi Score.
    - `League_Standings/top10_league_stable.png`: PNG file containing a table of the top 25 stablecoin pools by SoDeFi Score.

## Explanation of Columns

- `SD Score`: SoDeFi Score (7 Day Average)
- `Chain`: Blockchain network of the pool
- `Protocol`: Protocol of the pool
- `Symbol`: Symbol of the pool
- `TVL (Millions)`: Total Value Locked in millions
- `TVL Change (7D)`: Percentage change in TVL over the last 7 days
- `APY (%)`: Annual Percentage Yield
- `7D APY (%)`: 7 Day Average APY

## License

This project is licensed under the MIT License.
