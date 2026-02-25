🛒 Supermarket Sales Performance Analysis
Exploratory Data Analysis & Animated Visualization using Python

📌 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on a supermarket sales dataset sourced from Kaggle. The goal is to uncover patterns in revenue, customer behavior, product performance, and cost structures across multiple cities using animated and interactive visualizations.
The analysis simulates the kind of data-driven decision support a business analyst would provide to sales, marketing, and operations teams — answering questions like:

Which product lines drive the highest gross income?
How do cost of goods sold (COGS) vary across cities and customer types?
What is the relationship between unit price and customer ratings?
Which payment methods correlate with higher revenue?


📂 Dataset

Source: Kaggle – Supermarket Sales Dataset
Records: 1,000 transactions
Cities Covered: Mandalay, Naypyitaw, Yangon (Myanmar)
Key Variables: Unit price, Quantity, Product line, Gross income, COGS, Rating, Payment method, Customer type, City


🎯 Objectives

Analyze the relationship between unit price and gross income across product lines
Identify the most profitable product lines by gross margin
Compare city-wise gross margin performance
Evaluate customer ratings by product line and city
Examine payment method preferences and their impact on revenue
Visualize variable correlations using animated heatmaps
Analyze COGS distribution by product line, city, and customer type


🛠️ Tech Stack
ToolPurposePython 3.xCore programming languagePandasData manipulation and aggregationNumPyNumerical computationsMatplotlibStatic and animated charts (FuncAnimation)SeabornCorrelation heatmapsPlotly ExpressInteractive animated scatter plotsGoogle ColabDevelopment environment

📊 Key Analyses & Findings
1. Unit Price vs. Gross Income

A positive but non-linear relationship exists between unit price and gross income
Gross income increases more rapidly at lower unit price ranges, then slows at higher price points
Naypyitaw recorded the highest single-transaction gross income of 49.65 in the Fashion Accessories category

2. Product Line Performance

Fashion Accessories generated the highest gross income overall
Accessories showed the highest gross margin percentage (~160%), making it the most profitable product line
Travel & Lifestyle had the lowest gross margin (~60%)

3. City-Wise Gross Margin

Naypyitaw consistently outperformed other cities in gross margin (60–140% range)
Mandalay ranked second (40–100%), with Yangon performing lowest (20–80%)

4. Correlation Analysis

Quantity, Total, COGS, and Gross Income are highly correlated (≥0.98), confirming expected revenue relationships
Unit Price and Rating show a weak negative correlation (-0.15), suggesting customers are slightly less satisfied at higher price points
Tax (5%) shows moderate correlation with revenue metrics

5. Payment Method Analysis

Gross income varies significantly across payment methods within the same time period
Certain payment methods show stronger association with higher-value transactions

6. COGS by Customer Type

Member customers in Yangon show notably different COGS patterns vs. Normal customers in Health & Beauty and Home & Lifestyle
Naypyitaw shows relatively consistent COGS across customer types


📁 Project Structure
supermarket-sales-analysis/
│
├── 045057_Project1.ipynb       # Main analysis notebook
├── supermarket_sales.csv       # Dataset (source: Kaggle)
└── README.md                   # Project documentation

▶️ How to Run

Clone this repository or open the .ipynb file in Google Colab
Upload supermarket_sales - Sheet1.csv to your Colab environment
Run all cells sequentially
Animated charts will render inline via HTML() display

bash# If running locally
pip install pandas numpy matplotlib seaborn plotly
jupyter notebook 045057_Project1.ipynb

💡 Business Insights Summary
QuestionFindingMost profitable product lineFashion AccessoriesBest performing cityNaypyitawHighest margin categoryAccessories (~160% gross margin)Price-rating relationshipHigher price → slightly lower ratingKey revenue driversQuantity, COGS, and Gross Income are tightly linked

🔮 Future Scope

Build a Power BI / Tableau dashboard for real-time sales monitoring
Apply time-series forecasting to predict future gross income
Perform customer segmentation using clustering (K-Means)
Conduct A/B analysis on payment method impact on basket size


🙏 Acknowledgements

Dataset: Kaggle – Supermarket Sales
Visualization references: Matplotlib & Plotly documentation
Development environment: Google Colab


👤 Author
Vinay Kumar
PGDM – Big Data Analytics & Marketing | FORE School of Management, Delhi
