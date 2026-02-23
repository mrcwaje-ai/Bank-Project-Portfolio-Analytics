# Bank Project Portfolio Analytics
Author: Mark Roland Waje  
Role Focus: Data Analytics | Banking Transformation | Portfolio Governance  

## Executive Summary

This project develops an integrated analytics framework to evaluate project portfolio performance, FTE savings realization, and capital efficiency within a banking environment.

The objective is to shift from traditional project status reporting toward value-driven portfolio governance.

Using Python, SQL, and Power BI, this project simulates how a Philippine bank can strengthen financial oversight of its strategic initiatives.

## Problem Statement

The bank lacks an integrated analytics framework to systematically monitor project portfolio performance, validate FTE savings realization, and prioritize capital allocation based on measurable ROI, resulting in potential capital inefficiency and overstated benefit projections.

## Data

- Project Management Dataset
https://www.kaggle.com/datasets/mayarmohamedswilam/project-management

- Salary Prediction Dataset
https://www.kaggle.com/datasets/rkiattisak/salaly-prediction-for-beginer

- Bank Marketing Dataset
https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing

These datasets were combined to simulate:
- Project financial performance
- Estimated FTE savings impact
- Revenue-related performance scenarios

## Methodology

1️⃣ Data Engineering — Python (Google Colab)
- Data cleaning
- Dataset merging
- Cost variance calculations
- FTE savings modeling using salary data
- ROI computation

2️⃣ Data Modeling — SQL (Mode.com)
- Structured transformation
- Aggregation by department, project type
- Portfolio KPI generation
- Prioritization scoring logic

3️⃣ Data Visualization — Power BI
- Executive-level dashboard design
- Portfolio Overview page
- Benefits Realization dashboard
- ROI distribution and prioritization visuals

## Insights

1. Portfolio Financial Health & Efficiency
Capital Discipline: The portfolio shows strong financial control with a Total Actual Cost of 166.15M against a Portfolio ROI of 11.60%. While the overall ROI is healthy, the "Actual Cost vs ROI%" scatter plot reveals a heavy concentration of "Low ROI" projects (72.73%) consuming significant capital.

Budget Precision: The "Planned vs. Actual Cost" analysis indicates high maturity in budgeting across most departments. However, Credit Risk and Operations show minor cost overruns (negative cost variance), whereas IT and Marketing are currently operating under budget, suggesting potential for capital reallocation.

<img width="929" height="523" alt="image" src="https://github.com/user-attachments/assets/db14b62f-37d6-4ff3-ba2a-0d9392fef899" />

2. Strategic Value Realization (FTE Savings)
High-Impact Departments: Operations and Marketing are the primary engines for efficiency, contributing nearly 50% of the total 19.28M FTE savings.

The "Productivity Sweet Spot": Small-to-medium-sized projects (costing < 1.5M) are delivering the highest density of ROI. High-cost projects ( > 2.5M) tend to see diminishing returns in percentage-based ROI, suggesting that "micro-transformations" may be more efficient than "megaprojects."

<img width="929" height="505" alt="image" src="https://github.com/user-attachments/assets/ebad54b7-a918-46fc-ad2d-39c5050510eb" />

3. Project Prioritization & Risk
**High-Yield Leadership**
The top tier of the portfolio is driven by high-performing initiatives primarily within Credit Risk and Operations.

Portfolio Benchmarks: Top-performing projects like "The Coding Expert" (72.40% ROI) and "Switch and Swift" (63.13% ROI) demonstrate high efficiency while maintaining positive cost variances.

Average Top Performance: The top 5 projects by ROI maintain an impressive average ROI of 60.32%, significantly lifting the overall portfolio health.

**Critical Risk & Variance Exposure**
While high-ROI projects are succeeding, a subset of the portfolio is experiencing significant capital erosion.

Cost Variance Concerns: The bottom 5 projects are currently responsible for a cumulative negative cost variance of -1.69M.

Underperformance Alert: Projects such as "The Principal of Change" and "Code Change Group" show significant budget overruns exceeding -280k each, despite delivering relatively low ROI (13%–15%).

Zero-Value Initiatives: Project "Skill Up" in Marketing represents a critical risk, showing 0.00% ROI and a negative cost variance of -325k, indicating a total lack of benefits realization.

<img width="922" height="504" alt="image" src="https://github.com/user-attachments/assets/bd99ef78-8831-4459-8f26-7db9725f9f67" />

## Recommendations

1️⃣ Strengthen Benefits Realization Governance
Recommendation:
Implement a formal Benefits Realization Framework requiring:
- Pre-approval quantified FTE baseline
- Post-implementation validation after 3–6 months
- Mandatory reporting to Portfolio Steering Committee

Why it matters:
Prevents inflated benefit projections that distort capital planning.

2️⃣ Introduce ROI-Based Stage Gate Reviews
Recommendation:
At 50% project completion:
- Recalculate updated ROI
- Reassess continuation vs termination
- Reallocate budget if needed

Impact:
Prevents capital being trapped in underperforming initiatives.

3️⃣ Rebalance Portfolio Toward Automation & Analytics
Data shows automation delivers:
- Higher FTE realization
- Lower variance
- Stronger ROI

Strategic Action:
Increase allocation toward:
- Core banking automation
- Data analytics infrastructure
- Process digitization

Reduce allocation to:
- Manual process redesign without system support

4️⃣ Improve Cost Estimation Discipline
Introduce:
- Historical variance benchmarking
- Standard cost buffers by project complexity
- Independent financial review before approval

5️⃣ Create a Portfolio Value Dashboard for the Board
Move from: “Project Status Reporting”
To: “Capital Efficiency & Value Reporting”

Monthly board pack should include:
- Portfolio ROI
- FTE savings realized
- Cost variance trend
- Top 10 value-creating projects
- Bottom 5 capital-draining projects
