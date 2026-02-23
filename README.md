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

1️⃣ Portfolio Financial Performance

🔎 Finding 1: Cost Variance Concentration

35–45% of projects show negative cost variance (Actual > Planned).
IT-heavy projects tend to exceed budget more frequently.
Large-scale transformation initiatives show higher variance volatility.

Board-Level Interpretation:
Cost overruns are not random — they are concentrated in high-complexity projects. This signals either:
- Underestimation at approval stage
- Scope creep
- Weak financial controls during execution

<img width="930" height="507" alt="image" src="https://github.com/user-attachments/assets/ace95e9b-ab3d-46f1-a3c8-1a49ef5568d7" />

2️⃣ FTE Savings Realization (Core Banking Relevance)

🔎 Finding 2: Planned vs Actual FTE Savings Gap
- Several projects forecast FTE reduction but actual realized savings lag by 20–30%.
- Process automation projects produce the highest realized FTE efficiency.
- Manual process reengineering projects underperform expectations.

Board-Level Interpretation:
The bank is strong at automation-driven productivity gains, but weaker in organizational change adoption.

This is critical because:
- FTE savings directly impact Cost-to-Income Ratio
- Overstated savings distort capital allocation decisions

3️⃣ ROI Distribution Across Portfolio

🔎 Finding 3: ROI Concentration
- Top 20% of projects contribute ~60–70% of total ROI.
- Several low-ROI projects consume material capital.
- Some high-priority projects show negative ROI at interim review.

Board-Level Interpretation:
The portfolio may be over-diversified with low-return initiatives.

Capital may be better concentrated in:
- High-automation programs
- Customer acquisition & digital revenue projects
- Data & analytics transformation initiatives
<img width="960" height="529" alt="image" src="https://github.com/user-attachments/assets/cbab9896-c89b-44a6-81eb-a9837191773c" />

4️⃣ Portfolio Prioritization Misalignment

🔎 Finding 4: Priority vs Financial Return
- Not all “High Priority” projects yield high ROI.
- Some medium-priority projects outperform financially.

Board-Level Interpretation:
Prioritization may be based on:
- Strategic narrative
- Departmental influence
- Regulatory pressure

But not always on quantified value realization.

<img width="922" height="506" alt="image" src="https://github.com/user-attachments/assets/1f111cb3-c47b-441b-9bc7-8ccfcb615fb6" />

These metrics enable structured transformation oversight and capital discipline.

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
