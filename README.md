# Marketing Campaign A/B Test Analysis
Statistical analysis of a marketing campaign's effectiveness using A/B testing methodology to determine the impact of paid advertising versus public service announcements (PSA).

## Key Findings
- Treatment group (paid ads) showed 43.09% lift in conversion rate
- Statistically significant results (p < 0.0001)
- Conversion rates:
  - Control (PSA): 1.79%
  - Treatment (Ad): 2.55%

## Technical Details

### Dataset Overview
Dataset from [Kaggle](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing)
- Total sample size: 588,101 impressions
- Control group: 23,524 impressions
- Treatment group: 564,577 impressions

### Statistical Methods
1. **Chi-Square Test**
   - Chi-square statistic: 54.01
   - Degrees of freedom: 1
   - P-value: < 0.0001

2. **A/B Test**
   - 95% confidence intervals calculated for both groups
   - Clear separation between control and treatment groups
