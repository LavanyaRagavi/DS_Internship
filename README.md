Data Science Internship Assignment — Web3 Trading Team
📊 Project: Trader Behaviour vs Market Sentiment Analysis

Candidate: Lavanya S

📍 Overview

This project analyzes how trader behavior — such as trading volume, profitability, and trade side — aligns or diverges from Bitcoin market sentiment (Fear vs Greed).
By combining trading data from Hyperliquid with the Bitcoin Fear & Greed Index, this study explores behavioral patterns that influence profitable or risky trading phases.

🧩 Objectives

To study the relationship between market sentiment and trader activity.

To identify when traders are most active — during Fear or Greed.

To analyze how profitability and risk vary across sentiment levels.

To uncover insights that can support smarter trading strategies.

📂 Project Structure
ds_LavanyaS/
├── notebook.ipynb            # Main Google Colab notebook
├── csv_files/                  # Raw and processed datasets
│   ├── historical_data.csv
│   ├── fear_greed_index.csv
│   └── merged_trader_sentiment.csv
├── outputs/                    # Saved charts and visuals
│   ├── buy_sell_behaviour.png
│   ├── daily_profit_trend.png
│   ├── heatmap.png
│   ├── profit_comparison_count.png
│   ├── trade_count.png
|   ├──trade_sizenvolume.png
└── ds_report.pdf               # Final summarized report

🗂️ Datasets

Trader Data (Hyperliquid Historical Data)

Contains execution price, trade size, side, leverage, PnL, and timestamps.

~2,11,000 records of individual trade activity.

Bitcoin Fear & Greed Index

Daily classification of Bitcoin sentiment: Extreme Fear, Fear, Neutral, Greed, Extreme Greed.

⚙️ Data Preparation Steps

Converted Timestamp IST to valid datetime and extracted date.

Merged both datasets using date, resulting in a unified dataset for sentiment-based analysis.

📊 Exploratory Data Analysis (EDA)

Key visualizations and insights include:

Trade Count by Sentiment — Trading frequency across sentiment phases.

Profitability by Sentiment — Boxplot of Closed PnL comparing Fear vs Greed.

Correlation Heatmap — Relation between Size USD, Execution Price, Closed PnL, and Fee.

🧠 Key Insights

Trader activity peaks during Fear phases — driven by volatility and reactive trading.

Profitability is highest during Extreme Greed — showing bold yet high-risk trading.

Market extremes (both Fear and Greed) bring greater volatility — potential for big gains or losses.

Sentiment acts as a reliable behavioral indicator influencing trading strategy outcomes.

📈 Sample Outputs
Visualization	Description

	Number of trades across market sentiments

	Trader profitability distribution during Fear vs Greed
🧮 Technologies Used

Python: Pandas, NumPy, Matplotlib, Seaborn

Environment: Google Colab

Version Control: GitHub

Visualization Export: Matplotlib + PNG outputs

Report: PDF summary (ds_report.pdf)

🚀 How to Run This Project

Open the Colab Notebook:
🔗 Click here to view notebook:
https://colab.research.google.com/drive/1evu-OyLzg88EbxtDzfcGIn2pkBkynPMM?usp=drive_link

Clone this GitHub Repository:
🔗 GitHub Repo — LavanyaRagavi/DS_Internship

git clone https://github.com/LavanyaRagavi/DS_Internship.git


Run the notebook cells sequentially:

Load datasets

Data cleaning and merging

Exploratory Data Analysis

Visualization and interpretation

Outputs will be stored automatically in the /outputs/ folder.

📘 Report Summary

The ds_report.pdf file includes:

Project objectives and dataset overview

Data preparation process

Visual insights from EDA

Key findings and conclusion

🧾 Conclusion

This analysis demonstrates that trader decisions are strongly influenced by market sentiment.
Trading volume and volatility rise during Fear periods, while Extreme Greed yields the highest average profits — revealing both opportunities and risks tied to emotional market cycles.


💼 LinkedIn Profile
 https://linkedin.com/in/lavanya-s-232885281

Note:
This project was developed as part of the Web3 Trading Team — Data Science Internship Assignment, showcasing end-to-end data handling, EDA, and insight generation skills.
