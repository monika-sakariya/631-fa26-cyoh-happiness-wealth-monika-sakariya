# Testing the Easterlin Paradox: Wealth vs. Happiness
Choose Your Own Hypothesis (CYOH) Project

| Element | Project Specification |
| :--- | :--- |
| **Working Title** | *Testing the Easterlin Paradox: Resampling Analysis of Wealth and Subjective Well-Being* |
| **Data Source & Provenance** | World Happiness Report raw tables (Gallup World Poll, UN Sustainable Development Solutions Network; downloaded from worldhappiness.report). |
| **Target Population** | Globally surveyed nations with reported Log GDP per capita and Life Ladder scores. |
| **Comparison Groups** | **Group A:** Top 25% Log GDP per capita (High Income) <br> **Group B:** 50th–75th percentile Log GDP per capita (Upper-Middle Income). |
| **Null Hypothesis ($H_0$)** | The distribution of life evaluation scores is identical between top-quartile and third-quartile nations; wealth labels are interchangeable. |
| **Test Statistic ($\delta^*$)** | Absolute difference in median life ladder scores ($|\text{Median}_A - \text{Median}_B|$). |
| **Permutation Test** | Two-group label permutation with 10,000 resamples to generate an empirical null distribution. |
| **Bootstrap Metrics** | 1. Difference in Means ($\bar{x}_A - \bar{x}_B$, CLT-governed) <br> 2. Difference in Medians ($\text{Median}_A - \text{Median}_B$, Non-CLT). |
| **Core BS-Audit Vulnerabilities** | 1. Cultural response bias across countries on the 0–10 Cantril Ladder. <br> 2. Disproportionate sampling of urban vs. rural citizens in polling. |
