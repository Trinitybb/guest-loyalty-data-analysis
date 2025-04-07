# guest-loyalty-data-analysis

SQL + Python project for analyzing guest loyalty behavior and purchasing patterns.

## Technologies Used:
- Python 3.x
- SQLite (for data storage and management)
- Pandas (for data manipulation)
- Matplotlib / Seaborn (for data visualization)
- Jupyter Notebook (for analysis and results)

## Overview
This project involves the analysis of guest loyalty data to uncover patterns in purchasing behavior, loyalty status, and trends over time. The goal is to provide insights into the most valuable guests, spending patterns based on loyalty tiers, and spending trends over time.

## Data
The data used for this analysis is structured into two main tables:
- **'guests'**: Information about each guest, including their loyalty status and other basic details.
- **'transactions'**: Guest transaction records, including the amount spent and transaction dates.

## Analysis
The analysis is done by using SQL queries to extract relevant insights, and Python is used for data manipulation and visualization. The key analyses conducted are:

- **Spending by Loyalty Tier**: Analyzing which loyalty tier spends the most.
- **Average Spending by Guest**: Determining which guest has the highest average spending.
- **Trends Over Time**: Investigating spending patterns over time, including spikes in transactions on specific dates.

## Visualizations
Below are some key visualizations generated from the data:

1. **Loyalty Tier Spending**:
   - This barplot shows the total spending for each loyalty tier.
   - **Observation**: The highest spending is observed among **Platinum** and **Gold** loyalty tiers. This indicates that these guests make larger purchases, which could be targeted with exclusive offers or rewards to maintain engagement.

2. **Average Spending per Guest**:
   - A barplot showing the average spending per guest.
   - **Observation**: The guest with the highest average spending is **Liam Brown**, followed closely by **Ava Johnson**. These individuals could be considered for personalized offers or recognition to enhance customer loyalty.

3. **Spending Over Time**:
   - A lineplot that shows how total spending changes over time.
   - **Observation**: The highest spending month is **March**, showing a significant spike in guest spending. This could be attributed to seasonal factors or special promotions during that month, indicating that March is a high-revenue period for the business.

## Technologies Used
- **Python** (Pandas, Matplotlib, Seaborn)
- **SQLite** for database management
- **Jupyter Notebooks** for analysis

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/guest-loyalty-analysis.git
