# Retail_Sales_Promotions_Demand_Forecasting

# Project Background

LegalPath Online is a fictional digital legal-document platform that helps customers create wills, powers of attorney, and business-formation documents online. The company invests in paid search to attract high-intent users who are actively looking for affordable, self-service legal-document solutions

This portfolio project analyzes LegalPath Online’s synthetic Google Ads performance data for January 2024. The objective was to identify the keyword clusters, devices, and campaign themes that generated the most efficient conversions and highest return on ad spend, then translate the findings into practical budget and campaign-optimization recommendations.

# Data Structure and Initial Checks

The dataset represents paid-search performance at a keyword or keyword-cluster level for a one-month period. It is structured to allow performance comparisons across campaign themes, intent types, and devices.

| Data area           | Example fields                                                          | Purpose                                         |
| ------------------- | ----------------------------------------------------------------------- | ----------------------------------------------- |
| Campaign attributes | Campaign, ad group, keyword cluster, sample keyword, match type, device | Defines the search theme and traffic segment    |
| Delivery metrics    | Impressions, clicks, CTR, spend, average CPC                            | Measures visibility, engagement, and media cost |
| Conversion metrics  | Conversions, conversion rate, CPA                                       | Evaluates acquisition efficiency                |
| Value metrics       | Conversion value/revenue, ROAS, profit contribution                     | Evaluates commercial return                     |
| Optimization fields | Quality Score, landing-page experience, recommendation category         | Supports practical optimization decisions       |

Key calculations used in Excel included:

1. CTR: (Clicks ÷ Impressions) × 100

2. Conversion rate: Conversions÷Clicks×100

3. CPA: Spend÷Conversions

4. ROAS: Revenue÷Spend

# Proposed Cluster Definition

Keywords were assigned to seven proposed performance clusters using conversion rate, ROAS, CTR, device-level performance, and product intent. The framework converts keyword-level data into practical budget-management decisions for the fictional company, LegalPath Online.

| Cluster | Name                               | Definition                                                                                                                         | Budget implication                                        |
| ------- | ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| C1      | Will — High Converters             | Will keywords with Conversion Rate > 3.5% and ROAS > 1.8x; high-intent commercial searches.                                        | ⬆️ Expand/protect budget                                  |
| C2      | Will — Volume Growth Play          | Will keywords with CTR > 5% and 2.5% ≤ Conversion Rate ≤ 3.5%; exploratory or template-related searches with conversion potential. | ➡️ Test higher bids; optimize copy and landing pages      |
| C3      | POA — Core Performers              | POA keywords with Conversion Rate > 3% and ROAS > 1.5x; proven performers.                                                         | ⬆️ Expand budget                                          |
| C4      | POA — Emerging Opportunity         | POA keywords with 2% ≤ Conversion Rate ≤ 3% and solid CTR; early traction requiring optimization.                                  | ➡️ Hold budget; optimize funnel                           |
| C5      | LLC — Niche High-Value             | LLC keywords with ROAS > 1.8x and Conversion Rate > 2.5%, regardless of volume.                                                    | ⬆️ Defend; scale selectively                              |
| C6      | Device Specialist — Mobile Winners | Keywords where Mobile ROAS > Desktop ROAS × 1.20; mobile-first performance opportunity.                                            | ⬆️ Increase mobile bids; reduce inefficient desktop spend |
| C7      | Underperformers / Restructure      | Keywords with ROAS < 1.0x or Conversion Rate < 2%; inefficient or poorly matched traffic.                                          | ⬇️ Pause or restructure; test new copy and landing pages  |

# Executive Summary

The portfolio generated $45,000 in monthly spend, 613 conversions, an average CPA of $73.41, and a portfolio-level ROAS of 1.72x. Performance was uneven across clusters. Will-related and core POA terms drove efficient conversions and strong returns, while the LLC cluster consumed 24.0% of spend but returned only 0.89x ROAS with a $135 CPA—making it the clearest opportunity for immediate budget reallocation.

[Paid Search – Cluster Performance Dashboard.pdf](https://github.com/user-attachments/files/32077493/Paid.Search.Cluster.Performance.Dashboard.pdf)


## Insights gathered

* C1: Will—High Converters was the most efficient cluster. It delivered 109 conversions from $5,827 in spend, with the portfolio’s lowest highlighted CPA ($53) and highest ROAS (2.24x).

* C3: POA—Core Performers was the main scale driver. It accounted for 37.8% of spend and generated 252 conversions, while achieving the highest reported conversion rate of 4.38% and a 1.78x ROAS.

* Mobile traffic presented a scalable efficiency opportunity. C6 produced a 1.90x ROAS, approximately 20% higher than desktop according to the dashboard, despite representing only 3.0% of total spend.

* C2: Will—Volume Growth had strong volume but optimization potential. The cluster produced 139 conversions at a $64 CPA and 1.87x ROAS, suggesting that improved query control, ad copy, and landing-page relevance could increase efficiency further.

* LLC terms were the primary performance issue. C7 spent $10,789 and drove only 80 conversions, producing a $135 CPA and 0.89x ROAS; the underlying LLC keyword group was reported at roughly 0.72–0.77x ROAS.
  
## Recommendation

* Pause or sharply reduce LLC keyword investment immediately. Redirecting inefficient LLC spend can prevent an estimated $3,000–$3,500 in monthly waste while a revised landing page and value proposition are tested.

* Scale C1: Will—High Converters. Increase its budget by 25% and raise bids selectively by approximately 12%, while monitoring marginal CPA and ROAS to ensure returns remain stable as volume grows.

* Protect C3: POA—Core Performers. Maintain investment in this high-volume, high-conversion segment and test modest geographic bid adjustments to find additional profitable demand.

* Increase mobile bids for C6. Apply a +30% mobile bid adjustment and test a mobile-focused landing-page experience, since this segment demonstrated a ROAS advantage over desktop traffic.

* Improve C2 traffic quality. Add negative keywords such as “free,” “printable,” “how,” and “comparison,” and shift part of broad-match traffic toward phrase match to reduce low-intent clicks.

* Run a controlled 90-day test for C4: POA—Emerging. Test a dedicated landing page and expert-focused ad messaging, with a target of reducing CPA from $92 to roughly $75–$80 before making a major budget expansion decision


The dashboard’s modeled optimization path projects portfolio ROAS improving from 1.72x to 2.01x, with monthly profit increasing from $28,617 to $40,200 after full optimization. Because this is a synthetic case study, these projections should be presented as scenario estimates rather than realized business outcomes







