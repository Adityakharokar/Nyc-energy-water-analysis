* Nyc-energy-water-analysis
End-to-end analysis and machine learning on NYC Local Law 84 energy and water disclosure data.


-- NYC Energy & Water Data Analysis

-- Problem Statement
Analyze NYC building-level energy and water disclosure data (Local Law 84)
to understand performance patterns and predict ENERGY STAR scores using
machine learning techniques.

-- Dataset
- Source: NYC Open Data (Local Law 84 – Calendar Year 2016)
- Type: Government building disclosure dataset
- Description: Contains building characteristics, energy consumption,
  water usage, and ENERGY STAR performance scores.

-- Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

-- Approach
- Performed data cleaning by handling missing values, correcting data
  types, and removing high-missing and noisy columns.
- Conducted feature selection and preprocessing to prepare a clean
  modeling dataset.
- Built a baseline regression model and improved performance using a
  Decision Tree Regressor.
- Converted continuous ENERGY STAR scores (1–100) into performance grades
  (A–F) and reframed the problem as a classification task.
- Trained and evaluated a Random Forest Classifier on the graded target.

-- Results
- Decision Tree Regressor achieved **R² ≈ 0.77**, significantly improving
  over baseline regression.
- Random Forest Classifier achieved **~63% accuracy** with macro F1 ≈ 0.63
  on ENERGY STAR performance grades.

* Key Learnings
- Importance of data cleaning and feature handling in real-world datasets.
- How improper feature quality can limit model performance.
- Translating regression outputs into business-friendly classification
  outcomes.
