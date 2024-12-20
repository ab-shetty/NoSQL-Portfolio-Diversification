# NoSQL-Portfolio-Diversification


## Project Overview

This repository contains materials and code for a project exploring advanced analytics techniques applicable to the financial services industry. The focus is on leveraging tools like **Neo4j**, **MongoDB**, and **Redis** to analyze financial data, construct diversified portfolios, and provide real-time insights. The project includes graph-based portfolio diversification, live trading systems, and customer account dashboards.

---


## Key Features

### **1. Portfolio Diversification with Neo4j**
- **Objective:** Use graph-theoretic algorithms to construct diversified stock portfolios.
- **Steps:**
  - Fetch historical stock prices from the S&P 500 using APIs.
  - Compute pairwise correlations using Pearson coefficients.
  - Represent stocks as nodes and correlations as edges in a graph.
  - Apply algorithms like:
    - **Minimum Spanning Tree**: Identify low-correlation hubs.
    - **Degree Centrality**: Highlight stocks with minimal connections.
    - **Louvain Modularity**: Detect communities within the stock network.

### **2. Real-Time Trading Systems with Redis**
- **Objective:** Provide live trading signals and portfolio valuation updates.
- **Features:**
  - Use Redis as a middleware to fetch live price data via APIs.
  - Store position-level data and calculate metrics like profit/loss instantly.
  - Enable real-time alerts and notifications for traders.

### **3. Customer Dashboards with MongoDB**
- **Objective:** Build interactive dashboards backed by MongoDB to store and analyze client data.
- **Components:**
  - Store financial metrics such as asset holdings, valuations, and alerts in MongoDB collections.
  - Integrate APIs to provide live updates on portfolio performance.
  - Support long-term storage for historical analysis.

---

## Datasets

The `data` folder contains:
- **SP500.csv**: List of S&P 500 stocks used in analysis.
- **StockUniverse.xlsx**: Tracking changes within the composition of the S&P500.
- **stacked_correlations.csv**: Correlation matrix of stock returns.
- **stacked_correlations_no_diag.csv**: Correlation matrix excluding diagonal self-correlations and repeated pairs.

---


## Slides

The `slides` folder contains a PowerPoint presentation (`Project3 v1.0.pptx`) summarizing the project's goals, methods, and findings.

---

## Team Members


* Zeynep Dereli
* David Ding
* Abhishek Shetty
* Justin Sterling

