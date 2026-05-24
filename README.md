# Investment-Portfolio-plus-Risk-Analysis-Dashboard
📌 Project Overview:
	Developed an interactive finance analytics dashboard using Power BI to analyze investment portfolio performance, ROI, asset allocation, and investment risk.
	The project helps investors and financial analysts monitor portfolio growth, identify high-risk investments, and make data-driven financial decisions using advanced Power BI visualizations and DAX calculations.

🛠️ Tools & Technologies Used:
Power BI,
DAX,
Excel Dataset

📂 Dataset Tables Used:
	Investors Table,	
	Investments Table,
	Market Data Table,
	Risk Analysis Table
	
📊 Dashboard Features:
	Portfolio Performance Analysis,
	ROI & Profit Tracking,
	Risk Analysis Dashboard,
	Asset Allocation Analysis,
	Investor-wise Drill-through Analysis,
	Market Trend Visualization
	
🚀 Advanced Power BI Features Used:
	Drill-through,
	DAX Measures,
	KPI Cards,
	Data Modeling,
	Relationships,
	Interactive Visualizations

📈 Key KPIs:
	Total Investment,
	Current Portfolio Value,
	Total Profit,
	ROI %,
	Risk Score,
	High Risk Investment Count
	
🧠 Important DAX Formulas Used:

💰 Total Investment:
	Total Investment =SUM(Investments[Invested_Amount])
	
📈 Total Current Value:
	Total Current Value =SUM(Investments[Current_Value])
	
💹 Total Profit:
	Profit =[Total Current Value] - [Total Investment]
	
📊 ROI Percentage:
	ROI % =DIVIDE([Profit],[Total Investment]) * 100
	
⚠️ Risk Category:
Risk Category =SWITCH(TRUE(),Investments[Asset_Type] = "Crypto", "High Risk",
Investments[Asset_Type] = "Stock", "Medium Risk","Low Risk")

📊 Key Insights:
	Crypto investments generated highest ROI but had maximum risk,
	Mutual funds provided stable long-term returns,
	Diversified portfolios reduced overall investment risk,
	High-risk investors preferred crypto and stocks,
	Bonds showed low volatility and stable performance
	
🎯 Business Impact:
	Improved portfolio monitoring,
	Enhanced risk management,
	Faster investment decision-making,
	Better financial performance tracking,
	Improved investor analysis
	
✅ Conclusion:

This project demonstrates the use of Power BI for advanced finance analytics and investment risk management. The dashboard provides interactive insights into portfolio performance, ROI, and risk exposure using DAX, drill-through analysis, and financial KPI reporting.
<img width="764" height="439" alt="image" src="https://github.com/user-attachments/assets/03e1a85e-718e-4b8f-a135-4c59e6427298" />
<img width="764" height="446" alt="image" src="https://github.com/user-attachments/assets/924a8721-b898-46ce-bb59-738402c711df" />
<img width="773" height="429" alt="image" src="https://github.com/user-attachments/assets/14bbc9d1-9234-497f-af2a-d4ed3ec4de4e" />


