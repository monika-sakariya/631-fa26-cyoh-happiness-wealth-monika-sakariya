# Testing Wealth vs. Happiness (Easterlin Paradox)
**CYOH Project** | UST-631 Data Preparation and Analysis

## Project Scaffold

| Element | Specification |
| :--- | :--- |
| **Question** | Does happiness keep increasing with higher income, or does it level off? |
| **Data Source** | 2025 World Happiness Report (Gallup World Poll via worldhappiness.report). |
| **Population** | ~140 countries surveyed in the 2025 release. |
| **Group A** | Top 25% Log GDP per capita (High Income). |
| **Group B** | 50th–75th percentile Log GDP per capita (Upper-Middle Income). |
| **Null Hypothesis ($H_0$)** | Happiness scores are the same across both groups; income labels can be swapped randomly. |
| **Test Statistic** | Difference in medians: $|\text{Median}_A - \text{Median}_B|$. |
| **Permutation Test** | 10,000 label shuffles to create the null distribution. |
| **Bootstrap Metric 1 (CLT)** | 95% Confidence Interval for difference in **Means**. |
| **Bootstrap Metric 2 (Non-CLT)** | 95% Confidence Interval for difference in **Medians**. |

---

## The 5-Point BS-Audit

1. **Source:** Survey data from Gallup World Poll. Does it reach rural populations as well as city residents?
2. **Comparisons:** Do people from different cultures understand the 0–10 happiness scale in the same way?
3. **Too-good results:** If happiness plateaus, is it real or an effect of the 0–10 scale ceiling?
4. **Sanity check:** Does a 0.5-point shift on a 10-point scale make real-world sense for the wealth gap?
5. **Confirmation bias:** We might want to prove "money can't buy happiness." We must report the true data even if wealth strongly predicts happiness.
