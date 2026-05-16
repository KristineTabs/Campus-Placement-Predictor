# Campus Placement Predictor

**End-to-End Data Science Project**  
Analyzing what actually gets students placed and predicting their salary packages.

---

## 🎯 Project Objective

This project explores a realistic student placement dataset (~9,000 records) to:
- Understand key factors that influence campus placements
- Predict whether a student will get placed (Classification)
- Predict expected salary package in LPA (Regression)
- Provide actionable insights for students and colleges

---

## 🛠️ Tech Stack

- **Language**: Python
- **Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Modeling**: Scikit-learn, XGBoost (upcoming)
- **Dashboard**: Streamlit (upcoming)

---

## 📊 Dataset Highlights

- **Source**: [Kaggle - Student Placement & Salary Dataset (Skills based)](https://www.kaggle.com/datasets/amaymishra11/student-placement-and-salary-dataset-skills-based/data)
- **Total Students**: 9,000
- **Placement Rate**: ~85.58%
- **Average Salary** (Placed students): ~64.75 LPA
- Features include: CGPA, technical skills, internships, projects, college tier, backlogs, etc.

---

## 📁 Project Structure
```bash
Campus-Placement-Predictor/
├── notebooks/           # Jupyter notebooks (EDA, Modeling...)
├── data/                # Dataset (ignored in Git)
├── src/                 # Python scripts (future)
├── models/              # Saved ML models (future)
├── README.md
└── .gitignore
```
---

## ✅ Day 1 Completed

- Project repository setup on GitHub
- Initial Exploratory Data Analysis (`01_EDA.ipynb`)
- Target variable analysis (Placement & Salary distribution)

---

## 🔄 Next Steps (Planned)

- Proper feature engineering and null value handling
- Deep EDA (by branch, college tier, skills, etc.)
- Model building (XGBoost, Random Forest, etc.)
- Model interpretability using SHAP
- Interactive Streamlit Dashboard
