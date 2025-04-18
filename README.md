# IPL-DASHBOARD

### Dashboard Image : 
![Dashboard](https://github.com/user-attachments/assets/4a313387-30b0-42e6-a506-41d8b718bd59)



# 🏏 IPL Dashboard using Power BI

This project is a fully interactive IPL (Indian Premier League) Dashboard created using Power BI. It showcases insights from IPL matches, including player and team performance, season-wise trends, and venue analytics.

---

## 📁 Dataset

Data for this dashboard was sourced from:

🟡 Public APIs providing live and historical IPL data

🟠 CSV files containing match-level and ball-by-ball details

The combined data was cleaned, transformed, and modeled in Power BI to support a wide range of insights.

---

## Problem Statement

The Indian Premier League (IPL) is one of the most followed cricket leagues globally, generating a massive amount of data each season — including player statistics, team performance, match results, and venue records. However, this data is often scattered and presented in raw, unstructured formats that are difficult to analyze efficiently.

The challenge is to transform this complex, multi-seasonal IPL data into a visually intuitive and interactive dashboard that enables users — from cricket fans to analysts — to:

* Gain actionable insights into team and player performance

* Track season-wise and match-wise trends

* Compare stats across teams, seasons, and venues

* Identify top performers and consistent match-winners

* Make data-driven observations for cricket discussions or strategies

The goal is to build a Power BI dashboard that not only presents this information clearly but also allows users to interactively explore the data through filters, slicers, and dynamic visuals.

---

## ⚙️ Steps to Build the Dashboard

**Step 1**: Load the IPL dataset (CSV files) into Power BI Desktop.

**Step 2**: Open **Power Query Editor**. In the **View** tab under the **Data Preview** section, enable:
- Column distribution  
- Column quality  
- Column profile  

**Step 3**: Change column profiling to **"Based on entire dataset"** for accurate statistics.

**Step 4**: Perform data cleaning:
- Remove unnecessary columns  
- Rename headers for clarity  
- Ensure consistent formats (dates, text casing for teams/venues, etc.)

**Step 5**: Create relationships between multiple tables like:
- `Matches`  
- `Deliveries`  
- `Players`  
- `Teams`

**Step 6**: Define calculated columns and DAX measures such as:
- Total Runs  
- Total Wickets  
- Strike Rate  
- Economy Rate  
- Win Percentage  

**Step 7**: Apply a custom theme from the **View** tab to keep visual styling consistent.

**Step 8**: Add **slicers (filters)** for:
- Season  
- Team  
- Player  
- Venue   

**Step 9**: Use **card visuals** to display key metrics:
- Total Matches  
- Top Run Scorer  
- Leading Wicket Taker  
- Most Wins by Team  

**Step 10**: Add visuals like:
- Bar charts for team and player stats  
- Line charts for season-wise analysis  
- Pie/Donut charts for win distribution  
- Clustered charts for comparison metrics  

**Step 11**: Incorporate custom visuals from Power BI marketplace if needed (e.g., KPI indicators, rating visuals).

**Step 12**: Publish the report to the **Power BI Service** and enable sharing or embedding.

---

## 📊 Features

- Interactive Filters for Season, Team, Player, Venue  
- Visual Comparison of Team & Player Stats  
- DAX-based Metrics for Accuracy  
- Clean and Modern UI with Themes  
- Easy to Customize for Future Seasons

---

## 📎 Screenshots

![Dashboard_Overview](https://github.com/user-attachments/assets/4a313387-30b0-42e6-a506-41d8b718bd59)

![Dashboard Squads_Section](https://github.com/user-attachments/assets/7c9b64fb-fb36-4ab4-bec7-f7f3dbd912d7)

![Dashboard Most_Sixes_Section](https://github.com/user-attachments/assets/19517636-8f03-4f30-8da0-4ef712ec2751)

---

## 📥 Data Sources

🧮 CSV Files

🌐 Public Cricket API

Link: https://cricketdata.org/

---

## 💡 Inspiration

This project was inspired by this [YouTube tutorial](https://youtu.be/FnzOTJFPDAc), which guided the end-to-end creation of a cricket analytics dashboard using Power BI.

---

## 🧑‍💻 Author

Milan Sharma  
[www.linkedin.com/in/milansharma449] | [https://github.com/Milan-Sharma-449]

---
