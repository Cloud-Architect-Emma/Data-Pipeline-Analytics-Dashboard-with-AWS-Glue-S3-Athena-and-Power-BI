# Data Pipeline & Analytics Dashboard with AWS Glue, S3, Athena, and Power BI

This project demonstrates a complete data analytics pipeline using AWS services (S3, AWS Glue, Athena) and Power BI for data visualization. The objective is to process, analyze, and visualize e-commerce order data through a cost-effective, serverless architecture.

The project simulates a real-world business intelligence workflow. Raw transactional data is stored in Amazon S3, cataloged and transformed using AWS Glue, queried using Athena, and visualized with Power BI. Python was used for preliminary data analysis and CSV exports.

# Technologies Used:
- AWS S3: for storing raw and processed data
- AWS Glue: for ETL and data cataloging
- Amazon Athena: for running SQL queries on data in S3
- Power BI: for dashboard development
- Python: using pandas, seaborn, and matplotlib for data analysis and visualization

# Architecture:
The architecture consists of an S3 bucket to store the data, a Glue Crawler to catalog the schema, Glue jobs for data transformation (optional), Athena for querying the data, and Power BI for reporting. A detailed diagram is available in the project directory.

# Project Structure:
<pre>  data-pipeline-analytics-dashboard/
├── assets/
│   ├── Diagram/
│   │   └── architecture-diagram for Data Pipeline & Analytics Dashboard.JPG
│   ├── README/
│   │   ├── E-Commerce Sales Dashboard.JPG
│   │   ├── Python code for Analysis.JPG
│   │   ├── Python code for Analysis 2.JPG
│   │   ├── Python code for Analysis 3.JPG
│   │   ├── Sales Visualisation Product Category.JPG
│   │   ├── Sales Visualisation top customers.JPG
│   │   └── Sales Visualisation top products.JPG
├── data/
├── queries/
├── reports/
├── scripts/
└── README.md </pre>

# Visual Insights:
The analysis includes total sales by category, top products, and top customers. These were visualized in Power BI and the results are stored in the assets/README/ folder.

## Architecture

<p align="center">
  <a href="assets/Diagram/architecture-diagram%20for%20Data%20Pipeline%20%26%20Analytics%20Dashboard.JPG">
    <img src="Diagram/architecture-diagram%20for%20Data%20Pipeline%20%26%20Analytics%20Dashboard.JPG" alt="Architecture Diagram" width="600"/>
  </a>
</p>

## Screenshots and Visuals

<h3 align="center">Power BI Dashboard</h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/E-Commerce%20Sales%20Dashboard.JPG" alt="E-Commerce Sales Dashboard" width="800"/>
</p>


### Python Analysis Code  
<h3 align="center">Python Code for Analysis</h3>

<p align="center">
  <a href="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Python%20code%20for%20Analysis.JPG">
    <img src="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Python%20code%20for%20Analysis.JPG" alt="Python code for Analysis 1" width="300"/>
  </a>
  <a href="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Python%20code%20for%20Analysis%202.JPG">
    <img src="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Python%20code%20for%20Analysis%202.JPG" alt="Python code for Analysis 2" width="300"/>
  </a>
  <a href="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Python%20code%20for%20Analysis%203.JPG">
    <img src="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Python%20code%20for%20Analysis%203.JPG" alt="Python code for Analysis 3" width="300"/>
  </a>
</p>

### Visual Insights  
<h3 align="center">Sales Visualizations</h3>

<p align="center">
  <a href="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Sales%20Visualisation%20Product%20Category.JPG">
    <img src="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Sales%20Visualisation%20Product%20Category.JPG" alt="Sales Visualisation - Product Category" width="300"/>
  </a>
  <a href="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Sales%20Visualisation%20top%20customers.JPG">
    <img src="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Sales%20Visualisation%20top%20customers.JPG" alt="Sales Visualisation - Top Customers" width="300"/>
  </a>
  <a href="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Sales%20Visualisation%20top%20products.JPG">
    <img src="https://raw.githubusercontent.com/Cloud-Architect-Emma/Data-Pipeline-Analytics-Dashboard-with-AWS-Glue-S3-Athena-and-Power-BI/main/assets/Sales%20Visualisation%20top%20products.JPG" alt="Sales Visualisation - Top Products" width="300"/>
  </a>
</p>

# Python Analysis:
The scripts use pandas for data manipulation and seaborn/matplotlib for basic visualizations. The results were exported to CSV for Power BI consumption. These scripts can be found in the scripts/ folder and visuals in assets/README/.

# Steps to Reproduce:
1. Upload raw CSV data to Amazon S3.
2. Create and run an AWS Glue Crawler to catalog the data.
3. Use Amazon Athena to query and transform the data.
4. Optionally, use Python to perform further analysis and export CSVs.
5. Import the cleaned data into Power BI and build your reports.

# Contact:
Name: Emmanuela
Email: emmanuela_prince@yahoo.com
LinkedIn: https://www.linkedin.com/in/cloud-architect-emma

# License:
MIT License

Copyright (c) 2025 Emmanuela

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
