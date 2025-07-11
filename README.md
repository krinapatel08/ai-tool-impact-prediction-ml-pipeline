# 📊 AI Tool Impact Prediction - ML Pipeline

This project analyzes and predicts the impact of AI tools (e.g., ChatGPT, Copilot, Gemini) on college students' grades using a real-world 2025 survey dataset from Indian colleges.

---

## 🎯 Objective

To build a complete **ML pipeline** that predicts whether using AI tools improves academic grades based on student behavior, trust level, internet access, and study patterns.

---

## 📁 Dataset Overview

**Source:** Custom 2025 Survey (Indian college students)  
**Rows:** 496  
**Columns:** 16  
Includes attributes like:

- AI_Tools_Used
- Daily_Usage_Hours
- Trust_in_AI_Tools
- Impact_on_Grades (Target)
- Use_Cases
- Device_Used
- Internet_Access
- Awareness_Level

---

## 🔧 ML Pipeline Workflow

1. **EDA:** Correlation, distribution, and visual insights  
2. **Preprocessing:** Label encoding, null handling, feature selection  
3. **Modeling:** XGBoost classifier with `accuracy`, `recall`, `ROC AUC`  
4. **Explainability:** Feature importance with SHAP  
5. **Evaluation:** Confusion matrix and classification report  

---

## 📈 Results

- ✅ Achieved high accuracy (~85%)  
- ✅ Identified key features: `Trust_in_AI_Tools`, `Daily_Usage_Hours`, `Internet_Access`  
- ✅ SHAP plots used for model transparency

---

## 🧪 Sample Prediction Flow

```python
{
  "Daily_Usage_Hours": 3.5,
  "Trust_in_AI_Tools": 4,
  "Internet_Access": "High",
  "Use_Cases": "Exam Prep",
  ...
}
→ Predicted Impact_on_Grades: +2 (Positive)



👩‍💻 Author
Krina Patel
AI/ML Engineer | Data Science | NLP | ML Pipelines
⭐ If you found this useful, give it a ⭐ on GitHub!
