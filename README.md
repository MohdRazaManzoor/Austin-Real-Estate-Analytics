# Austin-Real-Estate-Analytics
Since you are building this for your portfolio to transition into a **Data Analyst** role, your README should focus on your ability to **solve business problems** and your **technical proficiency**.

Here is a professional structure you can copy and paste. I’ve tailored it to include the specific DAX and Python work we’ve done together.

-----

# Austin Real Estate Market Analysis (2018 - 2021)

**An interactive Power BI Dashboard exploring price trends, market segmentation, and educational impact in Austin, Texas.**

## 📊 Project Overview

This project analyzes over 15,000 real estate listings to provide actionable insights into the Austin housing market. The goal was to identify price drivers, analyze year-over-year (YoY) growth, and understand the relationship between property features (like school ratings) and final sale prices.

## 🚀 Key Features & Insights

  * **Dynamic Market Segmentation:** Classified properties into professional tiers (e.g., Core Market vs. Premium Estates) to analyze high-volume vs. high-value trends.
  * **YoY Growth Tracking:** Developed advanced DAX measures to calculate a **1.8x price multiplier** and YoY percentage changes across different cities.
  * **Seasonality Analysis:** Identified "Peak Months" for sales volume, revealing a consistent summer surge in the Austin market.
  * **Python Integration:** Leveraged Python libraries (Seaborn/Matplotlib) within Power BI for advanced statistical visualizations like Correlation Matrices and Scatter Plots.

## 🛠️ Tech Stack

  * **Tool:** Power BI Desktop
  * **Languages:** DAX (Data Analysis Expressions), Python
  * **Data Source:** Austin Housing Dataset (Kaggle/CSV)
  * **Visuals:** Custom Line Charts, Small Multiples, Treemaps, and Python-scripted visuals.

## 🧠 Advanced DAX Implemented

I used complex DAX to overcome data modeling challenges, including:

  * **Time Intelligence:** Using `DATEADD` and `USERELATIONSHIP` to handle inactive relationships for historical price comparisons.
  * **Context Manipulation:** Utilizing `CALCULATE` and `ALL` to bypass visual filters for accurate market-wide benchmarks.
  * **Dynamic Labels:** Creating smart card visuals that display text like "Mostly 1-2 Story" based on the data's statistical mode.

## 📈 Dashboard Preview



## 💡 How to Use

1.  Download the `.pbix` file.
2.  Open in Power BI Desktop.
3.  Use the **Market Segment** slicer to filter by price tier or the **City** slicer to see localized trends.
