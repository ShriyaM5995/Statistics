# Statistics
# 📊 One-Sample Hypothesis Testing (Z-Test)

This repo demonstrates how to perform a **one-sample hypothesis test** on a mean using a right-tailed test.

---

## 🔹 Problem Setup

- Null Hypothesis: **H₀: μ = 40**
- Alternative Hypothesis: **Hₐ: μ > 40**
- Significance Level: **α = 0.05**
- Sample Mean: **x̄ = 25**
- Sample Size: **n = 20**

We want to know whether this sample provides statistically significant evidence that **μ > 40**.

---

## 🔹 Formula Used

Test Statistic (Z):

\[
z = \frac{\bar{x} - \mu_0}{\sigma / \sqrt{n}}
\]

Decision Rule:

| p-value vs α | Conclusion |
|-------------|------------|
| p ≤ α | ✅ Reject H₀ |
| p > α | ❌ Fail to Reject H₀ |

---

## 🧠 Statistical Interpretation

- If we get **p < 0.05**, we conclude that **μ is likely > 40**
- Otherwise, the data **does not** support μ > 40

---

## 📁 Contents

| Folder/File | Description |
|------------|-------------|
| `notes/` | Detailed handwritten → formatted notes |
| `code/` | Python + Notebook for Z-Test automation |
| `data/` | (Optional) Sample dataset |
| `README.md` | Overview of the hypothesis-testing example |

---

## ▶️ Run Example Code (Python)

```bash
python code/z_test.py
