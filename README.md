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
<img width="480" height="269" alt="1" src="https://github.com/user-attachments/assets/0e6c2a21-dfb9-4875-9a5a-adb61e7af7e8" />
<img width="480" height="268" alt="2" src="https://github.com/user-attachments/assets/456a38d1-fd47-4495-9991-89894643303a" />
<img width="482" height="270" alt="6" src="https://github.com/user-attachments/assets/8ac0be92-2e40-4cee-ba84-c2db91f18179" />
<img width="480" height="268" alt="5" src="https://github.com/user-attachments/assets/527a928c-8084-4d7e-ad14-05821d437fb4" />
<img width="477" height="267" alt="4" src="https://github.com/user-attachments/assets/509cc7f8-c98d-4269-9065-a6238bee3a14" />
<img width="479" height="269" alt="3" src="https://github.com/user-attachments/assets/acb3a5e2-5af9-4b51-b2f9-0e1219175c60" />



## 💡 How to Use

1.  Download the `.pbix` file.
2.  Open in Power BI Desktop.
3.  Use the **Market Segment** slicer to filter by price tier or the **City** slicer to see localized trends.
