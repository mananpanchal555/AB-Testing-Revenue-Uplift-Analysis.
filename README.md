# A/B Testing & Revenue Uplift Analysis

## Executive Summary
This project measures the financial efficacy of a newly deployed enterprise mobile application for a hotel chain. Utilizing a **Difference-in-Differences (DiD)** methodology and a dataset of 4,000 user profiles, the analysis isolates the causal impact of app adoption on customer booking velocity and gross revenue.

## Business Value & Strategic Outcomes
* **ROI Quantification:** Proved that app adoption drove a statistically significant **$1,061 increase** in Average Revenue Per User (ARPU) post-launch, compared to a baseline $200 organic increase in the control group.
* **Customer Segmentation:** Analyzed spending behaviors across loyalty tiers to identify high-yield demographics for future digital marketing allocation.
* **Product Efficacy:** Validated the software development lifecycle (SDLC) investment by tying technical deployment directly to measurable financial uplift.

## Statistical Findings & Business Impact
| Metric | Control Group (Non-Adopters) | Treatment Group (App Adopters) | Business Insight |
| :--- | :--- | :--- | :--- |
| **Pre-Launch ARPU** | $4,188 | $4,275 | Both cohorts exhibited similar baseline spending prior to software intervention. |
| **Post-Launch ARPU** | $4,388 | $5,336 | App adoption triggered a massive divergence in spending behavior. |
| **Net Revenue Uplift** | +$200 | **+$1,061** | The application actively drives conversion and increases transaction volume. |
| **P-Value (Significance)** | N/A | < 0.001 | The uplift is statistically significant and not due to market variance. |

## Technical Stack
* **Language:** Python 3.x
* **Libraries:** Pandas (Data manipulation), SciPy (Statistical T-Testing), Seaborn/Matplotlib (Data Visualization).
