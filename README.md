# Aerofit Customer Analysis & Probability Study

## Project Overview
**Aerofit** is a leading brand in fitness equipment, offering treadmills, exercise bikes, and gym accessories. This project analyzes customer data for Aerofit's treadmill products to understand customer behavior, build profiles, and provide actionable business insights.  

The analysis focuses on:
- Descriptive statistics
- Outlier detection
- Customer profiling
- Probability analysis (marginal & conditional)
- Visualization and insights for business decisions

## Dataset
The dataset contains information of individuals who purchased a treadmill in the last three months.

**Features:**
- `Product Purchased`: KP281, KP481, KP781
- `Age`: Customer age in years
- `Gender`: Male/Female
- `Education`: Years of education
- `MaritalStatus`: Single/Partnered
- `Usage`: Average weekly treadmill usage
- `Income`: Annual income ($)
- `Fitness`: Self-rated fitness (1-5)
- `Miles`: Average miles walked/run per week

**Product Portfolio:**
| Product | Description          | Price ($) |
|---------|-------------------|-----------|
| KP281   | Entry-level treadmill | 1,500     |
| KP481   | Mid-level treadmill   | 1,750     |
| KP781   | Advanced treadmill    | 2,500     |

**Dataset Link:** [Aerofit_treadmill.csv](https://drive.google.com/file/d/1NBk1TFkK4NeKdodR2DxIdBp2Mk1mh4AS/view?usp=drive_link)

## Objectives
1. Perform descriptive analytics to create a customer profile for each treadmill product.
2. Construct contingency tables and compute:
   - Marginal probabilities
   - Conditional probabilities
3. Visualize customer demographics and relationships using:
   - Histograms, countplots, boxplots, heatmaps, pairplots
4. Detect outliers and analyze their impact on business decisions.
5. Provide actionable insights for product recommendations and marketing strategies.

## Steps Performed
1. **Data Exploration & Cleaning**
   - Checked data structure, types, and missing values
   - Converted categorical attributes to `category` datatype
2. **Descriptive Statistics**
   - Summary statistics (mean, median, min, max)
   - Outlier detection using boxplots
3. **Non-Graphical Analysis**
   - Value counts and unique attribute analysis
4. **Visual Analysis**
   - Univariate: histograms, countplots
   - Bivariate: boxplots, scatterplots
   - Correlation analysis: heatmaps, pairplots
5. **Probability Analysis**
   - Marginal probabilities of product purchases
   - Conditional probabilities by gender, marital status, and other features
6. **Customer Profiling & Recommendations**
   - Segmented customers based on purchase behavior and demographics
   - Recommended marketing and sales strategies

## Project Preview
### Sample Visualizations
**1. Distribution of Age by Product**
![Age Distribution](images/age_distribution.png)

**2. Treadmill Usage by Gender**
![Usage by Gender](images/usage_gender.png)

**3. Heatmap of Feature Correlations**
![Correlation Heatmap](images/correlation_heatmap.png)

> Note: Replace `images/...` with your actual saved plot paths in the repository.

## Key Insights
- KP281 mostly attracts younger, single customers with lower income.
- KP781 is preferred by male customers with higher fitness levels and higher income.
- Product usage frequency and miles run/week are strong indicators of product selection.
- Conditional probabilities reveal strong correlation between marital status, income, and treadmill choice.

## Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

## How to Run
1. Clone this repository:
```bash
git clone <your-repo-url>
