**Amazon Distribution Analysis**

This project simulates and analyzes Amazon's inventory operations using Monte Carlo simulation techniques. The goal of this project is to evaluate inventory metrics, such as cycle inventory, safety stock, average inventory, and service level.

Tools Used
- Microsoft Excel
- Monte Carlo Simulation (200 iterations)
- Probability Distributions

Problem Overview
Amazon must decide which warehouse to stock lightweight items for, taking into account key variables such as:
- Uncertain Customer Demand
- Tradeoffs between shipping costs, holding costs, and service levels

Simulation Logic
###  Key Inputs
| Input Variable         | Distribution Type             | Description                                |
|------------------------|-------------------------------|--------------------------------------------|
| **Weekly Demand**      | Normal(μ, σ)                  | Varies by region and product               |
| **Lead Time**          | Varies by region and product  | Assumed as Constant for the Model          |
| **Order Quantity**     | Varies by region and product  | Inventory replenishment amount             |
| **Holding Cost Rate**  | Fixed % for region and product| Cost of storing inventory weekly           |
###

## Output Metrics
- **Cycle Inventory**
- **Safety Stock**
- **Average Inventory**

  These metrics provide insights into operational efficiency and cost-performance tradeoffs across different stocking strategies.

## Applications
This project showcases:
- Quantitative modeling for decision-making
- Inventory Optimization
- Tradeoff Analysis between warehouses to maximize cost and reduce risk
