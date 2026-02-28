# **Bank Project Portfolio Analytics**
Portfolio Health • Benefits Realization • Capital Efficiency

## Executive Overview

This project develops an integrated analytics framework to evaluate project portfolio performance, FTE savings realization, and capital efficiency within a banking environment.

The objective is to shift from traditional project status reporting toward value-driven portfolio governance.

Using Python and Power BI, this project simulates how the bank can strengthen financial oversight of its strategic initiatives.

## Problem Statement

Today, we deploy significant capital across our project portfolio, yet we have **no integrated mechanism — effectively 0% structured monitoring** — to systematically measure whether capital allocation is optimized and benefits are actually realized.

We approve projects based on projected ROI and FTE savings, but we do not consistently track:
- Percentage of projected benefits realized post-implementation
- Share of capital allocated to bottom-quartile ROI projects
- Portfolio-level capital efficiency ratio
- Variance trends before overruns become material

If **even 5–10% of portfolio capital is misallocated**, the impact **directly translates into diluted ROE**, **pressure on cost-to-income ratio**, and **weakened capital productivity**.

Additionally, if projected FTE savings are overstated by even 10–20%, the assumed operating leverage embedded in our financial planning becomes unreliable.

In short, we are managing execution status — not value realization, thus the need from _zero structured monitoring_ to **a 100%, fully-structured governance mechanism**.

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
1. Data cleaning – Removed duplicates, handled missing values, standardized formats, and validated data integrity to ensure analytical accuracy.
2. Dataset merging – Joined multiple project, financial, and HR datasets using common keys to create a unified analytical model.
3. Cost variance calculations – Computed budget deviation by deriving the difference and percentage variance between planned and actual costs.
4. FTE savings modeling using salary data – Estimated workforce savings by converting reduced FTE counts into monetary value using average salary benchmarks.
5. ROI computation – Calculated return on investment by comparing realized financial benefits against total project cost.

2️⃣ Data Visualization — Power BI
1. Executive-level dashboard design – Built a structured, decision-focused reporting interface aligned to Board-level KPIs and strategic objectives.
2. Portfolio Overview page – Developed high-level visuals summarizing capital allocation, project distribution, and overall performance health.
3. Benefits Realization dashboard – Created analytics to track realized FTE savings, value delivery, and variance against targets.
4. ROI distribution and prioritization visuals – Designed comparative visuals to identify high-return projects and support value-based capital allocation decisions.

## Insights

1️⃣ Capital Efficiency & ROI Concentration

Portfolio ROI is positive, but capital concentration in low-efficiency projects limits overall performance.
Top-performing projects generate disproportionate value, suggesting reallocation opportunities.

<img width="926" height="524" alt="image" src="https://github.com/user-attachments/assets/ae899586-ae5b-4453-80d9-d9783e7c4f2b" />

 
2️⃣ Benefits Realization Gap

Planned FTE savings exceed actual realization in several departments, signaling need for post-implementation validation.


<img width="923" height="522" alt="image" src="https://github.com/user-attachments/assets/fb1c7b08-e50b-4e59-8c2e-fc047df68720" />

3️⃣ Variance Risk

Cost overrun patterns are clustered, not random — enabling targeted governance intervention.

<img width="921" height="513" alt="image" src="https://github.com/user-attachments/assets/7a03d455-72d1-40f3-adea-f4d455e44475" />

## Recommendations

1️⃣ Embed Value Governance in Stage Gates
Use ROI, FTE Realization %, and Cost Variance thresholds as continuation criteria.

Governance coverage to be achieved: 30%
This establishes ex-ante control — preventing low-value projects from progressing unchecked.

2️⃣ Reallocate Capital Using Efficiency Score
Shift funding toward high-efficiency projects identified in the Prioritization Engine page.

Governance coverage to be achieved: 20%
This introduces portfolio-level optimization, not just project-level control.

3️⃣ Institutionalize Benefits Validation
Mandate 3–6 month post-implementation FTE savings validation.

Governance coverage to be achieved: 30%
This closes the largest blind spot — realized value verification.

4️⃣ Implement Early Warning Dashboards
Deploy variance heatmap to portfolio committee monthly reviews.

Governance coverage to be achieved: 20%
This introduces continuous monitoring, not periodic review.

## What This Proposal Changes:

This framework introduces, for the first time:
- A quantified capital efficiency score per project
- Measurable benefits realization tracking (Planned vs. Actual %)
- Portfolio ROI concentration analysis
- Early-warning variance dashboards
- Scenario-based capital reallocation modeling

We move from 0% structured value monitoring to a governance mechanism capable of tracking portfolio efficiency at 100% project coverage.

This shifts portfolio oversight from reactive reporting to proactive capital optimization.

## Business Impact

If implemented:
- Improved capital productivity
- Stronger cost-to-income discipline
- Transparent portfolio governance
- Data-driven prioritization
