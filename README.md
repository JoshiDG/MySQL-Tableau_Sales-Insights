# MySQL-Tableau_Sales-Insights

## Problem Statement
Atliq is a hardware company which supplies networking hardware and periphirals to different clients. They are headquartered in Delhi with offices across India.

Sales for this company is declining. Sales director for the company "Bhavin Patel" wants to understand the reasons for the sales decline. Regional managers have a tendency to paint a rosy picture. So, Bhavin patel gathers excel files from these regional managers to understand real ground level infromation. 

Bhavin Patel Wants to know:
1. Revenue Breakdown by Cities
2. Revenue Breakdown by Year and Months
3. Top 5 customers by revenue and sales quantity
4. Top 5 products by revenue

We want to enable business decisions based on real data analytics. To create a workflow where data is stored in a SQL database in realtime, feeds automatically into the dashboard and gives Bhavin reports at regular intervals. 

He can dosn't have to call anyone, he can just look at the dashboard. 

## AIMS grid

### Purpose
- Unlock the sales insights which are not currently visible to decision makers. 
- Reduce the manual time taken to gather sales in formation by automating the process
- Provide decision support to the stakeholders by enabling them with ground level real time data

### Stakeholders
- Sales Director
- Marketing Team
- Custoemr Service Team
- Data & Analytics Team
- IT Team

### End Result
- Automated Tableau Dashboard which reports current realtime sales data to support data based decision making

## Data Exploration

- The data was extracted from companies data warehouse and received in the form of a SQL database
- The database contained 5 tables 
- <img width="694" alt="Screen Shot 2022-02-20 at 15 49 53" src="https://user-images.githubusercontent.com/92747557/154863803-bb1c6faa-33d2-4416-b064-2e390532c00b.png">

## Extract-Transform-Load (ETL)

### Creating a Star Schema in Tableau

- Fact Table
  - transactions
- Dimention Tables
  - customers
  - date
  - markets
  - products
<img width="558" alt="Screen Shot 2022-02-20 at 15 53 33" src="https://user-images.githubusercontent.com/92747557/154863948-81367e80-0983-4dc4-97b5-80643b505aec.png">

 
  
