# Area 51 Piercing: Marketing Research for Student Engagement

## Overview

Area 51 Piercing, a locally owned studio in Eugene, Oregon, estimated that only 25% of its customers were University of Oregon students — while its main competitor, High Priestess, drew approximately 75% of its business from students. This project investigated why that gap exists and how Area 51 could better market to the student population.

**The research question:** How should Area 51 market its services to students?

---

## Methodology

### Research Design
- **Exploratory phase:** Phone interviews with two local piercing shops + in-person interviews with 10 UO students
- **Descriptive phase:** 13-question online survey distributed to UO students

### Sample
- 54 complete responses
- Demographics: 78% male, 20% female, 2% non-binary; distribution across all undergraduate years

### Analytical Tools
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Statistical tests: chi-square, t-tests, ANOVA, correlation, regression
- Qualtrics (survey design)
- Excel

---

## Key Findings

| Finding | Result |
|---------|--------|
| Awareness of Area 51 | Only 24% of students familiar |
| Awareness of competitor (High Priestess) | 54% of students familiar |
| Top discovery channel | Word-of-mouth (3.68/5) |
| Top social media platform | Instagram (68% of votes) |
| Top traditional media | TV (51%) and billboards/signs (43%) |
| Most preferred promotions | Percentage discounts (50%), BOGO (20%), fixed discounts (19%) |
| Willingness to pay (average) | $48.45 per piercing |
| Minimum discount for unplanned piercing | 46% off on average |
| Interest in additional services (tattoos, haircuts) | Low — neutral (3.27/5) |

### Statistical Highlights
- Social media usage for discovery was significantly higher among underclassmen (3.55 vs. 2.95, p < .05)
- Women were significantly more likely to use word-of-mouth (4.45 vs. 3.48, p < .05)
- Women were also more willing to share personal information for discounts (4.18 vs. 3.24, p < .05)
- Offensive rebounding differential had a confidence interval containing zero — meaning it does not significantly predict winning in the NBA (relevant basketball crossover)

---

## Recommendations

Based on the findings, I recommended that Area 51:

1. **Increase student awareness** – Partner with student influencers, run Instagram campaigns, participate in campus events
2. **Run student-targeted promotions** – Focus on BOGO and percentage discounts (e.g., back-to-school offers)
3. **Stick to piercing only** – No evidence to support expanding into tattoos or haircuts
4. **Maintain current pricing** – Current prices align with student willingness to pay ($48–$50)

---

## Repository Contents

| File | Description |
|------|-------------|
| `area51_analysis.ipynb` | Jupyter notebook with full analysis (data cleaning, statistical tests, visualizations) |
| `executive_summary.pdf` | 1-page summary of findings and recommendations |
| `data/survey_responses.csv` | Anonymized survey data (54 responses) |
| `requirements.txt` | Python package dependencies |
| `README.md` | This file |

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/danieljporter34/area51-marketing-research.git

2. Install required packages:
   ```bash
   pip install -r requirements.txt

3. Launch Jupyter notebook:
  ```bash
  jupyter notebook area51_analysis.ipynb
