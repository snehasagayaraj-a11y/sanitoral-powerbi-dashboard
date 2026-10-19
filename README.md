# Sanitoral Project Portfolio Dashboard (Power BI)

This project is a Power BI dashboard built for the Project Management Office (PMO) of Sanitoral, an international company present in four regions and 52 countries. The PMO holds a large amount of project data but lacked a clear way to use it. The dashboard turns that data into a visual tool that helps directors decide which projects need attention, correction or a stop.

The portfolio covers 104 projects: IT projects (CRM implementation, six phases from A to F) and Marketing projects (launch of a new product, four phases from 1 to 4). Each project is monitored on three key indicators, cost, deadlines and deliverables, always compared with the plan. When any indicator deviates by more than 15 % from the forecast, the project is flagged as an alert. Across the portfolio, cost is 7.29 % above plan, duration is 13.43 % below plan and deliverables are 10.49 % below plan, and 73 of the 104 projects are in alert.

The report has three views for the three types of users. The CEO page gives a global overview with KPI cards, alerts by region, planned versus actual cost by project type and a table of projects in alert. The Regional Director page is filtered on one region and the Country Director page on one country, so each director only sees the projects they are responsible for. A world map coloured by schedule variance shows the countries where projects are most delayed, and tooltips give extra detail on hover. Slicers allow filtering by region, project type and project start year.

The data model was built from an Excel file with plans, actual costs, durations, deliverables, project types and locations. Data was cleaned in Power Query, relationships were organised around a project dimension, and all indicators and alerts were created with DAX measures. Country names were translated into English so the map could locate them.

Main assumptions: variances are calculated on each project's total values, alerts apply in both directions, and a project's start year is that of its first planned phase.

Tools: Power BI, Power Query, DAX, Excel.

Author: Sneha Sagayaraj, M2 Business Analytics, EDC Paris Business School.
