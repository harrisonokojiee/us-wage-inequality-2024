# us-wage-inequality-2024
A data storytelling project examining the 15x wage gap between the highest and lowest paying occupations in the U.S. — visualized with Python.

# U.S. Wage Inequality by Occupation (2024)

A data storytelling project examining how wages vary dramatically across occupations in the United States, using publicly available data from the Bureau of Labor Statistics.

---

## Project Overview

The U.S. employs over 150 million workers across hundreds of occupations — but the gap between the highest and lowest paying jobs is nearly **15x**. This project explores that inequality through exploratory data analysis and visualization.

---

## Key Findings

- Physicians and executives earn upwards of **$200,000+** annually while food service and manual labour roles sit near **$15,000**
- Even within a single occupation, the spread between the 10th and 90th percentile earner can exceed **4x**
- The national wage distribution is **right-skewed** — the median worker earns significantly less than the mean, pulled up by a small number of elite occupations

---

## Visualizations

| Chart | Description |
|---|---|
| Top & Bottom 20 Occupations | Highest and lowest paying jobs by median annual wage |
| Wage Spread by Occupation | 10th vs 90th percentile gap within individual occupations |
| National Wage Distribution | Histogram of median wages across all 818 occupations |
| Wage Concentration Curve | Employment-weighted cumulative wage bill share across workers |
| Predicted vs Actual Median Wage | Linear-model baseline prediction using 10th and 90th percentiles |

---

## Tools & Libraries

- Python 3
- Pandas / NumPy
- Matplotlib / Seaborn
- Google Colab

---

## Data Source

U.S. Bureau of Labor Statistics — [Occupational Employment and Wage Statistics (OEWS), May 2024](https://www.bls.gov/oes/tables.htm)

---

## How to Run

1. Clone this repository
2. Download the OEWS national dataset from the BLS link above
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```
4. Open the notebook in Google Colab or Jupyter
5. Place/upload `all_data_M_2024.xlsx` in the same working directory as the notebook
6. Run all cells top to bottom

### Output Files

Running the notebook generates:

- `chart1_top_bottom_wages.png`
- `chart2_wage_spread.png`
- `chart3_wage_distribution.png`
- `chart4_wage_concentration_curve.png`
- `chart5_predicted_vs_actual.png`

---

*Analysis by Harrison Okojie | [LinkedIn](https://linkedin.com/in/harrison-okojie-274373353) | [GitHub](https://github.com/busykimono)*
