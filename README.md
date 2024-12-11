xx
# DeFi TVL Visualization

## Overview

This project visualizes trends in the DeFi (Decentralized Finance) space over time. It generates various charts to analyze Total Value Locked (TVL), the number of projects, pools, and liquid staking pools across different blockchains.

## Features

- **Total Value Locked (TVL) Analysis**:
    - Bar charts showing TVL over time.
    - TVL by the largest chains.
    - Percentage change in TVL over 7 days for the largest chains.

- **Projects Analysis**:
    - Bar charts showing the number of projects over time.
    - Number of projects by the largest chains.
    - Change in the number of projects year-to-date for the largest chains.

- **Pools Analysis**:
    - Bar charts showing the number of pools over time.
    - Number of pools by the largest chains.
    - Change in the number of pools over 7 days for the largest chains.

- **Liquid Staking Pools Analysis**:
    - Bar charts showing TVL of liquid staking pools over time.
    - TVL by liquid staking protocols.
    - Percentage change in TVL over 7 days for liquid staking protocols.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/RazDwa1923/DeFi_TVL_Viz.git
    ```
2. Navigate to the project directory:
    ```sh
    cd DeFi_TVL_Viz
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Ensure the data file `DeFi_Global_DB.csv` is located in the `Data_Sets/Global_Data` directory.
2. Run the Jupyter Notebook `DeFi_TVL_Viz.ipynb` to generate the visualizations.
3. The generated charts will be saved in the `Figures` directory.

## Data

The data used in this project is sourced from the `DeFi_Global_DB.csv` file. The dataset includes information on various DeFi projects, pools, and their respective TVL.

## Dependencies

- pandas
- seaborn
- numpy
- matplotlib
- PIL
- datetime

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements

Special thanks to the contributors and the open-source community for their valuable resources and support.