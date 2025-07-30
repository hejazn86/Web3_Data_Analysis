# Ethereum Blockchain Explorer – Transaction & Miner Behavior Analysis

This project explores Ethereum blockchain data using Web3.py and Infura. It focuses on mining patterns, transaction activity, gas usage, and wallet behavior — all analysed and visualized using Python and Jupyter Notebooks. Designed as a portfolio project, it demonstrates data wrangling, analysis, and storytelling using real blockchain data.

---

## Problem Statement

Ethereum generates thousands of transactions per minute, offering a rich source of insights into economic activity, DeFi usage, and network congestion. However, raw blockchain data is difficult to analyze without context or visualization.

This project aims to:
- Understand miner behavior and efficiency
- Analyze gas fee trends and network load
- Identify high-activity wallets and outliers
- Track how transaction count, value, and gas usage vary over time

---

##  Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Ethereum-Blockchain-Explorer.git
cd Ethereum-Blockchain-Explorer
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Add your Infura Project ID in `main_web3.py` or `env` file:

    ```python
    infura_url = "https://mainnet.infura.io/v3/YOUR_PROJECT_ID"
    ```

4. Run the analysis script:

    ```bash
    python main_web3.py
    ```

