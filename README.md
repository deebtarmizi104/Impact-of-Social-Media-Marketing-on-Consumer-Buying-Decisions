# 📱 Impact of Social Media Marketing on Consumer Buying Decisions

> An analysis of how social media influences consumer confidence, trust, and purchasing behaviour using statistical tests and visual insights.

## 🧠 Project Overview

This project explores the influence of social media marketing strategies on consumer buying behaviour. Using survey responses from 136 participants, we analyzed how different platforms, content types, engagement levels, and demographics contribute to purchase decisions. Various statistical tests (t-test, ANOVA, regression, correlation, etc.) were applied to validate the hypotheses.

---

## 🎯 Objectives

- Examine the influence of social media marketing on consumer purchase decisions.
- Analyze how user engagement (likes, comments, shares) impacts trust and buying behaviour.
- Identify which platforms (e.g., Instagram, TikTok) have the greatest marketing impact.
- Explore the role of user-generated content and influencer marketing.
- Assess demographic differences (gender, age) in marketing influence.

---

## 📋 Data Collection

- Data Source: Google Forms survey
- Total Responses: 136
- Sections:
  - Demographics
  - Social Media Usage
  - Influence of Social Media Marketing
  - Perception & Trust
  - Actual Buying Behaviour

---

## 🧹 Data Preprocessing

- **Missing Values:** Mode imputation for Likert items
- **Encoding:**
  - Ordinal (Likert scale, age, income)
  - Binary (e.g., gender: 1/0)
  - One-Hot (e.g., occupation)
  - Multi-label binarization for platform/content selections
- **Normalization:** Title casing, whitespace trimming
- **Final Dataset:** `impact_df` (cleaned working copy)

---

## 📊 Exploratory Data Analysis (EDA)

- Gender and confidence: No significant visual difference
- Age and confidence: Consistent trust levels across age groups
- Heatmap: Positive engagement (likes/comments) ↔️ higher trust and purchase intention
- Tree map: Instagram and TikTok most used platforms

---

## 🧪 Hypothesis Testing & Results

### H1: Gender vs Confidence (T-test)
- ✅ **Result**: No significant difference (p = 0.5356)

### H2: Age vs Confidence (Kruskal-Wallis)
- ✅ **Result**: No significant difference (p = 0.425)

### H3: Engagement ↔ Purchase Likelihood (Spearman Correlation)
- ✅ **Result**: Significant positive correlation (r = 0.37, p < 0.001)

### H4: Impact of Social Media on Purchase (Regression)
- ❌ Multiple Linear Regression: Poor (R² = -0.21)
- ✅ Random Forest: Moderate performance (R² = 0.25)

### H5: Platform Differences (ANOVA)
- ✅ **Result**: No significant difference (p = 0.6528)

---

## 📈 Key Insights

- **Engagement matters more than platform**: Likes and comments build trust.
- **Gender and age do not significantly change buying confidence**.
- **Random Forest is a better predictor than linear regression** in this context.
- **Content quality & interaction outweigh platform preference**.

---

## 📁 Files

- `notebook.ipynb`: Complete analysis workflow in Jupyter Notebook
- `dataset.csv`: Cleaned dataset (if publicly shareable)
- `survey_form.pdf`: Sample questionnaire

---

## 📚 References

- Hajli, M. (2014). *Impact of social media on consumers*. Int. J. Market Res.
- Sokolova & Kefi (2020). *Credibility & parasocial interaction influence on Instagram*.
- Vierman et al. (2017). *Instagram influencers and brand attitudes*.
- And more (full list in the report)

---

## 🔗 Project Repository

[GitHub Repository – Social Media Marketing Impact](#)

📌 *Add your actual repo URL above once created.*

---

## 📌 Future Work

- Test more content types (video vs text vs UGC)
- Analyze longitudinal behaviour
- Compare micro vs macro influencer impact
- Improve model generalizability with more data

---
