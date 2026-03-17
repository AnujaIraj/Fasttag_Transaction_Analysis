# Fasttag_Transaction_Analysis
SQL Data Analysis Project on FASTag transactions to analyze toll revenue, traffic trends, failure rates, and operational insights using real-world structured data.
FASTag Transaction Analysis
Project Overview

This project analyzes FASTag toll transaction data to identify revenue trends, traffic patterns, transaction failures, and operational insights.
The analysis is performed using SQL queries on a structured dataset representing toll plaza transactions.

The objective is to simulate a real-world banking/transport analytics scenario where transaction data is analyzed to support business decision-making.

Business Problem

FASTag enables automated toll payments across highways. With thousands of transactions occurring daily, it becomes important to:
Monitor toll revenue
Identify peak traffic hours
Detect failed or reversed transactions
Analyze toll plaza performance
Identify abnormal transaction patterns
This project uses SQL to analyze FASTag transaction data and generate meaningful insights.
Dataset Description

The dataset contains simulated FASTag transaction records.

Column	                Description
txn_id	                Unique transaction ID
vehicle_id	            Vehicle registration number
plaza_id	              Toll plaza identifier
txn_date	              Transaction date
txn_time	              Transaction time
amount	                Toll amount charged
status	                Transaction status (SUCCESS / FAILED / REVERSED)
vehicle_type	          Vehicle category (Car / Truck / Bus)
bank_name             	Issuing bank
balance_before	        Wallet balance before transaction
balance_after	          Wallet balance after transaction

Tools & Technologies:
SQL
SQL Server / SSMS
Data Analysis
Window Functions
Aggregate Functions

SQL Analysis Performed:
The FASTag transaction dataset was analyzed using SQL to extract operational insights related to traffic patterns, revenue generation, banking performance, and transaction integrity.

1. Data Exploration
Initial analysis was performed to understand the dataset structure and basic metrics:
Total number of transactions
Date range of transactions
Number of unique vehicles
Number of toll plazas
Distribution of transaction statuses (SUCCESS, FAILED, REVERSED)

2. Revenue Analysis
Revenue insights were generated using successful transactions:
Total revenue generated across all toll plazas
Daily revenue trends
Monthly revenue analysis using year and month aggregation
Plaza-wise revenue comparison
Vehicle-type-wise revenue contribution
Identification of top revenue-generating toll plazas

3. Transaction Status Analysis
Transaction reliability and failure patterns were examined:
Total transaction count by status
Percentage of failed transactions
Percentage of reversed transactions
Toll plazas with the highest failure rates
Vehicle types associated with the most failed transactions

4. Time-Based Traffic Analysis
Temporal analysis was conducted to understand traffic patterns:
Peak transaction hours using hourly aggregation
Hour-wise revenue generation
Daily transaction trends
Identification of rush hours with highest traffic volume

5. Bank and Wallet Analysis
Bank performance and wallet consistency were analyzed:
Bank-wise transaction counts
Bank-wise transaction failures
Detection of wallet balance inconsistencies
Identification of transactions with negative balances
Verification of proper refund processing for reversed transactions

6. Advanced SQL Analytics
Advanced SQL techniques were applied to generate deeper insights:
Ranking toll plazas by monthly revenue using window functions
Identifying the most frequent vehicle per toll plaza
Calculating running cumulative revenue over time
Detecting duplicate transaction records

7. Key Insights
Peak traffic occurs during typical commute hours.
A small number of toll plazas generate the majority of revenue.
Some banks show higher failure rates than others.
Transaction validation checks ensure wallet balance consistency.
SQL window functions help identify revenue leaders and trends.

Project Objective:
This project demonstrates SQL-based data analysis skills including:
Data exploration
Business problem solving
SQL aggregation and filtering
Window functions
Analytical thinking
It simulates how a Data Analyst in a banking or transport analytics team would analyze transaction data.
