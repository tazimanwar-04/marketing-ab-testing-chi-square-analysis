# A/B Testing – Hypothesis Testing in Python

##  Project Overview

This project performs A/B Testing analysis on a marketing campaign dataset to evaluate whether displaying advertisements increases user conversion rates compared to a Public Service Announcement (PSA).

The analysis includes hypothesis testing using the Chi-Square test, confidence interval calculation, and business recommendation.

---

##  Business Problem

Does showing advertisements significantly increase conversion rates compared to PSA?

---

##  Hypothesis

Null Hypothesis (H0):
There is no difference in conversion rates between Ad and PSA groups.

Alternative Hypothesis (H1):
There is a significant difference in conversion rates between Ad and PSA groups.

Significance Level (α): 0.05

---

##  Tools Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Google Colab

---

##  Statistical Method

Chi-Square Test for Independence was used to compare conversion rates between:

- Treatment Group (Ad)
- Control Group (PSA)

---

##  Results

| Group | Total Users | Converted Users | Conversion Rate |
|-------|------------|----------------|----------------|
| Ad    | 564,577    | 14,423         | 2.55%          |
| PSA   | 23,524     | 420            | 1.78%          |

P-value: 1.99e-13

Since p-value < 0.05, we reject the null hypothesis.

---

##  Confidence Interval

Estimated improvement in conversion rate:

0.77 percentage points

95% Confidence Interval:

(0.59%, 0.94%)

---

##  Business Conclusion

The advertisement campaign significantly improves conversion rates.

It is recommended to continue running the ad campaign as it provides measurable and statistically significant improvement.

---

##  Project Files

- task11_abtest.ipynb – Full analysis notebook
- ab_test_summary.csv – Summary statistics
- final_recommendation.txt – Final business recommendation

---

## 🚀 Author

Tazim Anwar  
MCA Student | Data Analytics Enthusiast
