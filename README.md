# Web3 Data Analysis Project

This project fetches and analyzes blockchain data from the Ethereum network using Infura. It provides insights into block and transaction data, and visualizes various aspects of this data.


## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/Web3-Data-Analysis.git
    cd Web3_Data_Analysis
    ```

2. Install dependencies:

  

3. Add your Infura Project ID in `main_web3.py`:

    ```python
    infura_url = "https://mainnet.infura.io/v3/YOUR_PROJECT_ID"
    ```

4. Run the analysis script:

    ```bash
    python main_web3.py
    ```

## Analysis

The project performs the following analyses:
- Fetches and saves block data for the last 1000 blocks.
- Visualizes the number of transactions over time.
- Visualizes the gas used over time.
- Shows the distribution of transaction counts per block.
- Fetches transaction data for the latest block.
- Shows summary statistics and distribution of transaction values.
