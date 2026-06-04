# Grammy.com Web Analytics
**Tools:** Excel · PivotTables · XLOOKUP · A/B Testing · KPI Analysis  
**Program:** UT Global Career Accelerator — The Recording Academy  
**Date:** Fall 2024

---

## Overview
Analyzed web analytics data for The Recording Academy (Grammy Awards) to evaluate the business impact of splitting grammy.com and recordingacademy.com into two separate sites. The analysis covered three distinct audience segments, calculated core engagement KPIs, and concluded with a data-driven recommendation supported by a formal hypothesis test.

---

## Business Question
Did separating grammy.com from recordingacademy.com improve user engagement and should the sites remain separate?

---

## What I Did

### 1. KPI Analysis
Calculated the following metrics across three audience segments (pre-split, post-split grammy.com, post-split recordingacademy.com):
- **Bounce rate** — 40.2% vs. 41.6% across segments
- **Pages per session** — measure of content depth per visit
- **Average session duration** — indicator of audience engagement quality
- **Mobile user share** — identified via XLOOKUP join across data tables (73.7% mobile)

### 2. Audience Segmentation
Used IF logic and date-based filtering to split traffic into three periods:
- Pre-split (combined site)
- Post-split grammy.com (music fans)
- Post-split recordingacademy.com (music industry professionals)

### 3. A/B Hypothesis Test
Formally tested whether the difference in pages-per-session between site versions was statistically significant.

| | Value |
|---|---|
| Test type | Two-sample t-test (Excel Data Analysis Toolpak) |
| Null hypothesis | No difference in pages-per-session between site versions |
| Result | p ≈ 4.6e-103 |
| Conclusion | Reject null hypothesis at 95% confidence — difference is statistically significant |

### 4. Recommendation
Recommended maintaining the two separate sites based on:
- Improved retention metrics post-split
- Distinct audience intent (fans vs. professionals)
- Competitor analysis vs. the American Music Awards (AMAs)

---

## Key Findings
- The split improved engagement for both audiences by serving more targeted content
- 73.7% of grammy.com traffic is mobile UX optimization for mobile is a high-priority recommendation
- recordingacademy.com attracted a more engaged, lower-bounce audience (music professionals)

---

## Files
| File | Description |
|---|---|
| `Grammys_Project_Andres_Navarrete.xlsx` | Full Excel workbook with raw data, KPI calculations, pivot tables, and hypothesis test |

---

## Skills Demonstrated
`Excel` `PivotTables` `XLOOKUP` `IF/IFS formulas` `Data Analysis Toolpak` `A/B Testing` `Hypothesis Testing` `KPI Analysis` `Audience Segmentation` `Data-Driven Recommendation`
