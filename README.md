# HR Analytics Dashboard - Power BI (Employee Attrition Analysis)

![Power BI Logo](https://img.shields.io/badge/Power%20BI-FF0000?logo=powerbi&logoColor=white)
![Level: Beginner](https://img.shields.io/badge/Level-Beginner-brightgreen)

An interactive **HR Analytics Dashboard** built in Power BI to analyze employee attrition and provide actionable insights for HR teams.

##  Objective
To identify key factors driving employee attrition (why employees leave) and help reduce turnover through data visualization.

##  Key Insights
- **Attrition Rate**: ~16.1% (237 out of 1470 employees)
- Highest attrition in:
  - Age group 26-35
  - Salary ≤ ₹5,000/month
  - First 1-2 years of tenure
  - Job roles: Laboratory Technician, Sales Executive, Research Scientist
  - Education fields: Life Sciences & Medical
- Young, single, male employees show higher attrition risk.

##  Tech Stack
- **Tool**: Microsoft Power BI Desktop
- **Language**: DAX (Data Analysis Expressions)
- **Data Processing**: Power Query
- **Dataset**: HR Analytics CSV (1470 records)

##  Project Structure

HR-Analytics-PowerBI/
├── HR Analytics Dashboard.pbix          # Main Power BI file
├── data/
│   └── HR-Employee-Attrition.csv        # Raw dataset
├── screenshots/
│   ├── dashboard_overview.png
├── README.md
└── Project_Documentation.pdf

##  Features
- Interactive Department slicer (HR / R&D / Sales)
- Real-time KPI cards (Headcount, Attrition Rate, Avg Salary, Avg Tenure)
- Multiple charts: Bar, Donut, Table
- Fully responsive and interactive dashboard

##  Screenshots

<img width="1328" height="743" alt="Screenshot 2026-04-20 222257" src="https://github.com/user-attachments/assets/44ff71a2-a764-4424-ad9a-b2a2d1d55d76" />


##  How to Use
1. Download the `.pbix` file
2. Open in **Power BI Desktop**
3. (Optional) Refresh data if you modify the CSV
4. Interact with slicers and visuals

## Steps Performed
1. Data Import & Cleaning in Power Query
2. Created DAX measures for KPIs and calculations
3. Built interactive visuals and slicers
4. Designed professional layout with proper formatting

##  Dataset
Original dataset available in the `dataset/` folder or from the tutorial.

## License
This project is for learning/portfolio purposes.

---
