# Social Media Campaign Performance Dashboard

A Power BI analytics project designed to evaluate advertising efficiency, audience quality, and conversion performance across multiple social-media campaigns.

## Overview

This project analyzes a campaign dataset containing 1,143 ad records and measures how marketing spend translates into impressions, clicks, conversions, and approved outcomes. The dashboard was built to help marketing teams understand which age groups, genders, and campaign segments are generating the strongest engagement and business value.

The result is a decision-support dashboard focused on:
- spend efficiency
- click-through performance
- conversion quality
- audience segment optimization
- campaign-level performance comparison

---

## Project Objective

The core objective is to answer a practical business question:

How effectively is the ad budget converting impressions into clicks and approved conversions, and which audience segments show the strongest return?

This project helps identify:
- underperforming campaigns
- high-value customer segments
- expensive acquisition patterns
- optimization opportunities for future media planning

---

## Dataset Summary

The dashboard uses the file `data.csv`, which contains campaign-level marketing data with fields such as:
- `ad_id`
- `campaign_id`
- `fb_campaign_id`
- `age`
- `gender`
- `interest1`, `interest2`, `interest3`
- `impressions`
- `clicks`
- `spent`
- `total_conversion`
- `approved_conversion`

### Dataset size
- 1,143 rows
- 13 columns

### Campaign performance at a glance

| Metric | Value |
|---|---:|
| Total impressions | 78,552,672 |
| Total clicks | 13,293 |
| Total spend | $20,114.24 |
| Total conversions | 1,645 |
| Approved conversions | 585 |
| Click-through rate (CTR) | 1.69% |
| Cost per click (CPC) | $1.51 |
| Cost per approved action (CPA) | $34.38 |

### Formula highlights
- CTR = Clicks / Impressions = 13,293 / 78,552,672 = 1.69%
- CPC = Spend / Clicks = $20,114.24 / 13,293 = $1.51
- CPA = Spend / Approved Conversion = $20,114.24 / 585 = $34.38

---

## Key Insights from the Data

### 1. Audience quality is concentrated in a few segments
- The strongest age segment is `30-34`, with 4,433 clicks and 328 approved conversions.
- This demographic alone contributes a major share of overall conversion opportunity.
- `35-39` is the second-largest segment, with 3,005 clicks and 129 approved conversions.

### 2. Male audience dominates performance volume
| Gender | Clicks | Spend | Approved conversions |
|---|---:|---:|---:|
| M | 9,989 | $17,170.03 | 481 |
| F | 1,685 | $2,450.21 | 104 |

- Male traffic accounts for roughly 75% of all clicks and 82% of approved conversions.
- This suggests that targeting strategy is skewed toward male segments and may have a higher acquisition efficiency for this dataset.

### 3. Campaign-level concentration is very high
| Campaign ID | Clicks | Spend | Approved conversions |
|---|---:|---:|---:|
| 1178 | 9,577 | $16,577.16 | 378 |
| 936 | 1,984 | $2,893.37 | 183 |
| 916 | 113 | $149.71 | 24 |

- Campaign `1178` drives the majority of performance: 72.1% of all clicks and 64.6% of approved conversions.
- This indicates a strong campaign concentration and a clear opportunity to scale or optimize the highest-performing media source.

### 4. Performance is efficient but not yet premium-scale
- CTR is 1.69%, which is respectable for a broad digital campaign but still leaves room for optimization.
- CPA of $34.38 is acceptable for campaign testing, but better audience targeting could reduce waste.
- The dataset is best suited for budget reallocation toward high-converting segments rather than broad spend scaling.

---

## Audience Analysis

### Age segment comparison

| Age Group | Clicks | Impressions | Spend | Approved Conversions |
|---|---:|---:|---:|---:|
| 30-34 | 4,433 | 35,678,593 | $7,693.22 | 328 |
| 35-39 | 3,005 | 20,165,377 | $5,145.52 | 129 |
| 40-44 | 2,660 | 15,881,589 | $4,337.63 | 82 |
| 45-49 | 1,576 | 6,788,029 | $2,443.87 | 46 |

### Interpretation
- `30-34` is the most valuable demographic in terms of both volume and conversion count.
- `35-39` is the second strongest segment and may offer stable acquisition value.
- `45-49` has lower conversion volume but may still be relevant for quality targeting depending on campaign objective.

---

## Business Implications

This dashboard is useful for marketing decision-making because it transforms raw campaign data into measurable operational insights. The primary business takeaways are:
- allocate more budget toward `30-34` and `35-39` audiences
- increase focus on campaign `1178` and similar high-performing campaigns
- refine targeting strategy for male-heavy performance segments
- improve creative or landing-page strategy to increase conversion quality

---

## Dashboard Features

The Power BI dashboard includes:
- KPI cards for spend, clicks, CTR, CPC, and CPA
- audience performance by age group
- gender-level engagement and spend comparison
- campaign ranking by conversion impact
- interest-based analysis for segmentation strategy
- interactive filters by age, gender, campaign, and date range

---

## File Structure

```text
Social-Media-Campaign-Performance-Dashboard-main/
├── data.csv
├── SOCIAL MEDIA CAMPAIGN PERFORMANCE DASHBOARD.pbix
├── SOCIAL MEDIA CAMPAIGN PERFORMANCE DASHBOARD SCREENSHOT.png
├── README.md
└── LICENSE (if present in some variants)
```

---

## How to Use

1. Open the project folder.
2. Ensure Power BI Desktop is installed.
3. Open `SOCIAL MEDIA CAMPAIGN PERFORMANCE DASHBOARD.pbix`.
4. Refresh data if needed using the included CSV dataset.
5. Use the slicers and visuals to analyze:
   - age-based performance
   - gender-based spend and conversion patterns
   - campaign contribution by volume and quality
   - effectiveness of ad spend allocation

---

## Tools and Technologies

- Microsoft Power BI Desktop
- CSV dataset processing
- Data cleaning and KPI modeling
- GitHub project documentation

---

## Conclusion

This project demonstrates how a data-driven dashboard can convert large-scale marketing data into actionable business guidance. Based on the actual dataset, the campaign portfolio is working best in specific audience and campaign segments, especially among the `30-34` age group and campaign `1178`.

The strongest opportunity is not necessarily more spending everywhere, but smarter budget allocation to the segments and campaigns already showing the highest conversion efficiency.

---

## Summary

The dashboard clearly shows that the campaign portfolio produces:
- 78.55 million impressions
- 13,293 clicks
- 1,645 conversions
- 585 approved conversions
- 1.69% CTR
- $1.51 CPC
- $34.38 CPA

These metrics make the project a strong example of technical marketing analytics and campaign performance reporting in a business intelligence context.
