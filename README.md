# A/B Testing and Statistical Analysis

This project analyses a homepage button experiment for Eniac, a Spanish e-commerce company specialising in Apple products and related accessories.

The goal was to evaluate whether changes in button text and colour improved user engagement compared with the original homepage call-to-action.

This project demonstrates how A/B testing and statistical analysis can support product and UX decisions by separating small observed differences from meaningful business impact.

## Project Overview

Eniac's homepage originally used a white **"SHOP NOW"** button, which generated a click-through rate of around 2%.

To test possible improvements, the UX team designed three alternative button versions using different combinations of text and colour.

The experiment was conducted from **November 2 to November 16, 2021** and compared four button versions:

| Version | Button Text | Colour | Type |
|---|---|---|---|
| A | SHOP NOW | White | Control |
| B | SHOP NOW | Red | Variant |
| C | SEE DEALS | White | Variant |
| D | SEE DEALS | Red | Variant |

## Business Question

Which homepage button version performs best, and should Eniac replace the original button?

## Statistical Concepts Covered

This project applies core statistical concepts used in A/B testing and business experimentation:

- A/B testing methodology
- Inferential statistics
- Experimental design best practices
- Data and sampling methods
- Summarising numerical data
- Probability and random variables
- Probability distributions
- Normal distribution
- Sampling distribution of a statistic
- Central Limit Theorem
- Hypothesis testing
- Chi-square test
- P-value interpretation
- Statistical decision-making

## Analysis Approach

The analysis focuses on whether the new button designs created a statistically meaningful improvement in user engagement.

The workflow includes:

- Data quality checks
- Click-through rate calculation
- Contingency table creation
- Chi-square test for statistical significance
- Pairwise comparison between button versions
- Business interpretation of the results
- Final recommendation based on statistical and practical impact

## Tools Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Key Findings

- The button versions did not perform equally.
- The red button variants performed worse than the original white button.
- The text change alone showed limited improvement.
- The original white **"SHOP NOW"** button remained the strongest option when both engagement and business impact were considered.

## Recommendation

Eniac should keep the original white **"SHOP NOW"** button.

The tested alternatives did not provide a strong enough business case for replacing the control version. Future experiments should focus on clearer, product-specific call-to-action text while avoiding design changes that may reduce user engagement.

## Repository Structure

```text
notebooks/              Full A/B test analysis notebooks
supporting_notebooks/   Statistical foundations and earlier analysis notebooks
data/                   Experiment data files
