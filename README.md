# XAI_Machine_Learning_Court

This analysis explores a loan denial decision through the lens of explainable AI (XAI), presented in a courtroom-style format. The case centers on Jane Dow, a 37-year-old professional woman with a bachelor’s degree and an executive occupation, whose loan application was denied by a machine learning model.

## 📖 Project Overview

* **Objective:** Investigate why the model denied Jane’s loan and analyze whether the reasoning was consistent and fair.
* **Approach:** Apply three leading XAI techniques (SHAP, LIME, Anchors) to interpret the decision.
* **Format:** Courtroom-style analysis with **Prosecution** (argues unfairness) and **Defense** (justifies the denial).
* **Assigned Role:** I was assigned the **Defense**, focusing on consistency and reliability of the model’s reasoning.

## 🛠️ Methods and Tools

* **Dataset:** UCI Adult Income dataset
* **Model:** Random Forest Classifier (scikit-learn)
* **XAI Techniques:**
  * SHAP (SHapley Additive exPlanations)
  * LIME (Local Interpretable Model-agnostic Explanations)
  * Anchors (High-Precision Model-Agnostic Explanations)

## 📊 Results

* **SHAP:** Showed both positives (education, hours worked, occupation) and negatives (marital/relationship, no capital gains).
* **LIME:** Capital gain absence was the strongest negative; probability of approval is **30%**.
* **Anchors:** Denial rule applied consistently with **95+% precision**.

