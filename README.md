
---

## Tech Stack & Libraries

- Python
- pandas, numpy
- scikit-learn
- imbalanced-learn (ADASYN)
- seaborn, matplotlib

---

## Workflow

1. **Data Loading**
   - Reads structured data from CSV or Databricks FileStore.

2. **Preprocessing**
   - Train-test split
   - Feature scaling using `StandardScaler`

3. **Imbalanced Data Handling**
   - Applied **ADASYN** oversampling on training data

4. **Modeling**
   - Used `RandomForestClassifier` for classification
   - Evaluated using confusion matrix & classification report

5. **Visualization**
   - Confusion matrix heatmap
   - (Optional) Feature importance plot

---

## Results

- **Improved F1-score** and recall on minority class due to ADASYN
- **Random Forest** provides robust performance with minimal tuning

---



## Future Improvements

- Add ROC-AUC and precision-recall curve
- Use cross-validation for model robustness
- Try alternative models like XGBoost or LightGBM
- Build a CI pipeline for automated training & testing

---

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
