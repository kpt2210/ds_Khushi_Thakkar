# Trader Behavior vs Market Sentiment Analysis

**Author:** Khushi Thakkar  
**Date:** October 2025  

---

## Project Summary
This project analyzes how trader behavior changes with Bitcoin market sentiment, particularly during **Fear** and **Greed** phases.  
The main focus was to understand how trading performance, volume, and fees vary depending on overall market psychology.

The analysis combines **historical trading data** with the **Fear-Greed Index** to draw correlations between sentiment and trader outcomes.

---

## Work Overview
1. **Data Loading & Inspection**  
   - Imported and verified datasets for structure, missing values, and empty columns.  
   - Identified relevant numeric and categorical fields for analysis.

2. **Data Cleaning & Preprocessing**  
   - Converted date fields to a consistent datetime format.  
   - Ensured numeric columns such as PnL, Fee, and Trade Volume were properly typed.  
   - Removed or ignored fully empty columns to maintain data quality.

3. **Merging Datasets**  
   - Combined trader data with market sentiment data using date as the key.  
   - Verified merge accuracy and created a unified dataset for analysis.

4. **Feature Engineering & Aggregation**  
   - Aggregated metrics by sentiment category to measure:  
     - Average and median PnL  
     - Average fee  
     - Total trading volume  
     - Trade count  
   - Generated summarized tables to visualize trader performance under different market emotions.

5. **Exploratory Data Analysis (EDA)**  
   - Created multiple plots to study relationships between sentiment and trading behavior:  
     - Bar charts for PnL, Fee, and Volume vs Sentiment  
     - Boxplots showing profit distribution across sentiment phases  
     - Scatter plots linking trade size and profit  
     - Rolling averages to track short-term trends  
     - Correlation heatmaps between performance metrics and sentiment score  

6. **Advanced Insights**  
   - Detected anomalies in profit using a 2σ (two standard deviation) threshold.  
   - Highlighted unusual trading behavior and volatility patterns.  
   - Derived insights on how traders respond to extreme sentiment shifts.

---

## Key Observations
- **Higher risk-taking behavior** was seen during market Greed phases.  
- **Profit distribution** showed greater variability in Greed periods, suggesting increased volatility.  
- **Fee and trade volume** trends aligned with sentiment cycles, peaking during bullish sentiment.  
- **PnL anomalies** revealed rare but extreme trading outcomes, often around major sentiment changes.

---

## Deliverables
- **Notebook:** `notebook_1.ipynb` — Complete analysis and visualizations  
- **CSV Outputs:** Processed datasets in `csv_files/`  
- **Charts & Visuals:** All EDA results stored in `outputs/`  
- **Final Report:** `ds_report.pdf` summarizing insights  

---

**This project demonstrates my ability to connect financial data with market psychology, perform structured EDA, and communicate insights effectively.**
