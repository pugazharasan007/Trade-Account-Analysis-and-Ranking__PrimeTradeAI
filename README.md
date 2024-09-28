# Trade-Account-Analysis-and-Ranking__PrimeTradeAI
Trade Account Analysis and Ranking
**Overview**
The project processes the TRADES_CopyTr_90D_ROI.csv dataset to calculate metrics such as profit and loss (P&L), win rates, and the Sharpe Ratio, and ranks accounts based on a scoring system.

**Methodology**
*Data Cleaning:* Loaded the dataset, handled missing values, and processed the Trade_History column.
*Feature Engineering*: Calculated P&L, ROI, win rates, and maximum drawdown for each account.
*Ranking:* Developed a scoring system using:
    * P&L: 50%
    * Win Positions: 30%
    * ROI: 20%
**Results**
The analysis produced a ranked list of the top 20 trading accounts, detailing their scores and performance metrics.
