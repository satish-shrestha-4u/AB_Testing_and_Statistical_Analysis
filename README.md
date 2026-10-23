# 📈 A/B Testing and Statistical Analysis

This project analyses a homepage button experiment for **Eniac**, a Spanish e-commerce company specialising in Apple products and related accessories.

The goal was to evaluate whether changes in **button text and colour** improved user engagement compared with the original homepage call-to-action.

The project demonstrates how **A/B testing and statistical analysis** can support product and UX decisions by distinguishing small observed differences from meaningful business impact.

---

## 📌 Project Overview

Eniac's homepage originally used a white **"SHOP NOW"** button, which generated a click-through rate of around 2%.

To test possible improvements, the UX team designed three alternative button versions using different combinations of text and colour.

The experiment ran from **November 2 to November 16, 2021** and compared four button versions:

| Version | Button Text | Colour | Type |
|:---:|---|---|---|
| **A** | SHOP NOW | White | 🎯 Control |
| **B** | SHOP NOW | Red | 🧪 Variant |
| **C** | SEE DEALS | White | 🧪 Variant |
| **D** | SEE DEALS | Red | 🧪 Variant |

---

## 🎯 Business Question

**Which homepage button version performs best, and should Eniac replace the original button?**

---

## 🧠 Statistical Concepts

The analysis applies core statistical concepts used in A/B testing and business experimentation:

- 🧪 A/B testing methodology
- 📐 Experimental design
- 📊 Inferential statistics
- 🎲 Probability and random variables
- 📈 Probability distributions
- 🔔 Normal distribution
- 📏 Sampling distributions
- 🧮 Central Limit Theorem
- 🧪 Hypothesis testing
- 📊 Chi-square testing
- 🔢 P-value interpretation
- 💼 Statistical decision-making

---

## 🔬 Analysis Approach

The analysis evaluates whether the alternative button designs produced a statistically meaningful improvement in user engagement.

### Workflow

```text
📥 Experiment Data
        ↓
🔍 Data Quality Checks
        ↓
📊 Click-Through Rate Calculation
        ↓
🧮 Contingency Tables
        ↓
🧪 Chi-Square Test
        ↓
🔎 Pairwise Comparisons
        ↓
💡 Business Interpretation
        ↓
🎯 Final Recommendation
```

---

## 🛠️ Tools & Technologies

- 🐍 **Python**
- 🐼 **Pandas**
- 🔢 **NumPy**
- 📐 **SciPy**
- 📊 **Matplotlib**
- 📈 **Seaborn**
- 📓 **Jupyter Notebook / Google Colab**

---

## 💡 Key Findings

- The four button versions did **not perform equally**.
- 🔴 The red button variants performed worse than the original white button.
- 📝 Changing the button text alone showed limited improvement.
- 🎯 The original white **"SHOP NOW"** button remained the strongest option when both engagement and business impact were considered.

---

## ✅ Recommendation

**Eniac should keep the original white "SHOP NOW" button.**

The tested alternatives did not provide a strong enough business case for replacing the control version.

Future experiments should focus on **clearer, product-specific call-to-action text** while avoiding design changes that may reduce user engagement.

---

## 🗂️ Repository Structure

```text
notebooks/
    A complete A/B test analysis notebook

supporting_notebooks/
    Statistical foundations and earlier analysis notebooks

data/
    Experiment data files
```

---

## 🎯 Project Outcome

This project demonstrates how **statistical testing can turn experimental data into practical product decisions**.

Rather than relying only on observed differences in click-through rates, the analysis combines **hypothesis testing, statistical significance, and business impact** to determine whether a change should actually be implemented.
