# Data Jobs Analysis Dashboard

## 📌 Overview
This repository contains an interactive Power BI dashboard designed to analyze the data professional job market. The dashboard provides a comprehensive view of approximately 479K job postings, tracking market trends over the year 2024. It features a macro-level industry overview alongside a dynamic drill-through capability for granular role analysis.

## 📊 Dashboard Features

### 1. High-Level Market Overview
The main page offers a broad analysis of the data job landscape:
* **Key Performance Indicators:** Displays the total job count (479K), median hourly salary ($47.62), and median yearly salary ($113K) across all collected data.
* **Jobs Over Time:** A line chart visualizing the volume of job postings from January 2024 to November 2024, highlighting a general downward trend in posting volume over the year.
* **Salary Comparisons:** A scatter plot comparing median hourly versus yearly salaries across various roles, illustrating the compensation hierarchy from Data Analysts up to Machine Learning Engineers.
* **Role Breakdown:** A horizontal bar chart and a detailed data matrix showing job counts, salary metrics, and trend sparklines broken down by specific job titles like Data Engineer, Data Scientist, and Business Analyst.

### 2. Dynamic Drill-Through Analysis
The dashboard utilizes a powerful drill-through button to allow users to dynamically analyze individual job titles in depth. For example, drilling into the "Data Analyst" role reveals:
* **Role-Specific Salaries:** Gauge charts displaying the specific median yearly ($90K) and hourly ($33) salaries for the isolated role.
* **Work Requirements:** Donut charts breaking down Work From Home (WFH) availability (10% True, 90% False) and Degree requirements (39% True, 61% False).
* **Geographic Distribution:** A global map visualization showing exactly where these specific jobs are located, demonstrating heavy concentrations in North America and Europe.
* **Sourcing & Job Types:** Insights into where to find these jobs (e.g., LinkedIn, BeBee, Indeed) via a bar chart, and a treemap detailing the breakdown of employment types, highlighting that full-time positions (88.00K) strictly dominate the market.

## 📂 Repository Structure
* `Job_Dashboard.pbix`: The primary Power BI dashboard file containing the data model, interactive visuals, and drill-through pages.
* `README.md`: Project documentation and usage guide.

## 🚀 How to Use
1. Download the `Job_Dashboard.pbix` file to your local machine.
2. Open the file using Power BI Desktop.
3. On the main "Data Jobs Dashboard" page, select a specific job title from the "Select Job Title" dropdown or click on a role within the table/visualizations.
4. Click the **Drill through job title** button to seamlessly navigate to the detailed breakdown for that specific career path.
