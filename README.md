# Quality Performance & Risk Management Dashboard (Power BI)

## 📊 Project Overview
This project involves the development of a comprehensive interactive dashboard designed to monitor and optimize operational quality and risk. By analyzing over **130K tasks**, the solution provides actionable insights into employee performance and process efficiency.

## 🛠️ Technical Implementation & DAX Engineering
- **Advanced DAX Formulas:** Developed custom measures using the `DIVIDE` function and complex logic to calculate critical KPIs:
  - **Quality Score:** Measuring overall accuracy (Calculated as `1 - Defects%`).
  - **Sampling %:** Tracking the audit coverage relative to total tasks.
  - **Fatal Error Rate:** Identifying high-risk operational failures.
- **Data Modeling:** Structured the data to support hierarchical analysis (**Supervisor to Employee level**) to meet complex business requirements.
- **Advanced Interactivity:** Implemented a **Play Axis** on scatter plots to visualize the temporal evolution of defects relative to sampling volume, providing a 4D view of quality trends.

## 📈 Data Visualization & Interactivity
- **Interactive Reporting:** Designed a 13-point dashboard for real-time KPI tracking.
- **Dynamic Analysis:** Integrated **Gauge charts** for immediate goal visualization and **Scatter charts** to analyze the temporal correlation between samples and defects.
- **Geospatial Insights:** Utilized **Map visuals** to track and compare performance across different work locations.
- **Custom Tooltips:** Developed specialized **EMP Tooltips** for granular, employee-level performance deep-dives without cluttering the main view.

## 💡 Business Insights & Impact
- **Risk Mitigation:** Enabled the proactive identification of operational risks by visualizing **Fatal Error** trends and outliers.
- **Operational Excellence:** Provided Supervisors with a data-driven tool to monitor their teams, leading to targeted process optimization and quality improvement.
- **Critical Thinking:** Applied custom business logic to aggregate multi-source data into a single source of truth for decision-making.

