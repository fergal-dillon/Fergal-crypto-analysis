# Fergal-crypto-analysis
SQL queries and datasets for cryptocurrency transaction analysis. 

# Crypto Transaction Analysis (2025)

This repository contains SQL queries and CSV datasets analyzing Bitcoin (BTC) and Ethereum (ETH) transactions, focusing on high-value and high-frequency activity.

---

## Queries

### 1. Top 10 Bitcoin Wallets by Transaction Volume
- **SQL:** `top_10_btc_wallets_transaction_volume.sql`
- **CSV:** `top_10_btc_wallets_transaction_volume.csv`
- **Description:** Aggregates all Bitcoin outputs and lists the top 10 wallets by total transaction value.

### 2. Top 10 Ethereum Wallets by Total Deposit Value (2025)
- **SQL:** `top_10_eth_high_value_deposits_2025.sql`
- **CSV:** `top_10_eth_high_value_deposits_2025.csv`
- **Description:** Aggregates ETH deposits in 2025 to show the wallets with the highest total incoming value.

### 3. Top 10 Ethereum Wallets by Number of Deposits (2025)
- **SQL:** `top_10_eth_high_count_deposits_2025.sql`
- **CSV:** `top_10_eth_high_count_deposits_2025.csv`
- **Description:** Aggregates ETH deposits in 2025 to show wallets with the highest number of transactions.

### 4. Top 10 Ethereum Wallets by Rapid In-and-Out Activity (2025)
- **SQL:** `top_10_eth_rapid_activity_2025.sql`
- **CSV:** `top_10_eth_rapid_activity_2025.csv`
- **Description:** Combines ETH deposits and withdrawals to identify wallets with rapid or high-value activity per hour.

---

## Notes

- All SQL queries were run using **Google BigQuery** on public crypto datasets.  
- CSV files contain the exported results of the queries.  
- All queries are designed for reproducibility and easy inspection on GitHub.

---

