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
   - Lift: 43.09%
   - P-value: < 0.0001
   - Statistically Significant: Yes

### Visualization
Two main visualizations were created:
- Sampling distribution under null hypothesis with observed difference
![sampling distribution under null hypothesis](https://github.com/user-attachments/assets/4423f16b-d4c1-408c-97c6-9626a7014f8b)

- Conversion rates comparison with 95% confidence intervals
![conversions with 95% confidence intervals](https://github.com/user-attachments/assets/54865626-2b09-406c-be8f-e3ae431cf548)
