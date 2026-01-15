# 📌 Project Title

Cricket Analytics SQL Case Study – Match, Team & Player Performance Insights

## 📌 Project Overview

This project is a SQL-based analytical case study focused on evaluating cricket match outcomes, team performance, and individual player contributions. The assignment simulates real business-style analytical questions commonly asked in data analyst interviews, requiring structured thinking, clean SQL logic, and performance-based evaluation.

The analysis answers 21 complex problem statements covering batting, bowling, fielding, match results, consistency, impact scoring, and ranking using SQL.

### 📌 Business Objective

The objective of this assignment is to:

Analyze player and team performance across multiple matches

Identify top performers, consistent players, and high-impact contributors

Evaluate match competitiveness and winning margins

Demonstrate advanced SQL querying skills used in real-world analytics roles

#### 📌 Dataset Description

The dataset includes structured cricket data with:

Match details (teams, date, location, results)

Player-level performance (runs, wickets, catches, stumpings, run-outs)

Team participation and outcomes

Player roles (batsman, bowler, all-rounder, etc.)

## 📌 Key Questions Solved

This case study answers questions such as:

Best batting average across all matches

Team with highest win percentage

Player with highest contribution to team runs in a match

Most consistent player using standard deviation logic

Closest match victories based on run margins

Players winning most Player of the Match awards

High-impact players using a custom impact score formula

Ranking players using window functions

Cumulative and running impact analysis by match date

## 📌 Skills & Concepts Demonstrated

Core SQL Skills

Complex JOINs (multi-table joins)

GROUP BY with aggregations

HAVING filters

Subqueries & CTEs

WINDOW FUNCTIONS (RANK, DENSE_RANK, cumulative sums)

Conditional logic using CASE WHEN

Analytical Concepts

Batting averages & win percentages

Contribution analysis

Consistency measurement using standard deviation

Impact score modeling

Ranking and comparative performance analysis

## 📌 Impact Score Logic

To evaluate overall player contribution, an Impact Score was calculated as:

Runs × 1.5  
+ Wickets × 25  
+ Catches × 10  
+ Stumpings × 15  
+ Run Outs × 10


Only players who participated in at least 3 matches were included to ensure fairness and statistical reliability.

## 📌 What I Have Done in This Assignment

Translated business-style analytical questions into optimized SQL queries

Designed logic to measure performance, consistency, and impact

Applied window functions for ranking and running totals

Ensured data accuracy and fairness using participation thresholds

Structured queries in a clear, readable, and interview-ready format

Focused on decision-making insights, not just query output

## 📌 Why This Project Is Relevant for MNC Data Analyst Roles

Mirrors real interview SQL case studies

Demonstrates ability to handle complex analytical requirements

Shows structured problem-solving and metric design

Highlights experience with performance evaluation and ranking logic

ATS-friendly keywords:
SQL, Data Analysis, Window Functions, CTE, Aggregation, Business Insights

## 📌 Tools Used

SQL (MySQL / SQL Server Management Studio 21 / PostgreSQL compatible syntax)

Google Colab Notebook (for structured query presentation)

## 📌 How to Use

Clone the repository

Review SQL queries question-wise

Run queries on a compatible SQL database

Interpret results for business insights

## 📌 Conclusion

This project demonstrates structured data analysis using SQL to evaluate performance, consistency, and impact in a sports dataset. The approach emphasizes accuracy, clarity, and meaningful metric design to support data-driven insights.
