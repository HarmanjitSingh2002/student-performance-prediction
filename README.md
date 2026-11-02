# Student Performance Prediction

A Python machine learning portfolio project that explores study-related factors and predicts a student's final academic score.

## Dataset Information
`student_performance.csv` contains 1,000 **synthetic practice records** generated for this project. It contains study hours, attendance, previous scores, absences, assignment average, parent support, internet access, extracurricular activities, and final score. It does not contain real student records.

## Files
- `student_performance_prediction.ipynb` — complete Jupyter Notebook
- `student_performance.csv` — synthetic practice dataset
- `requirements.txt` — Python dependencies

## Technologies
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Jupyter Notebook.

## Workflow
1. Load and inspect data.
2. Explore score distributions and relationships.
3. Prepare numerical and categorical features.
4. Train Linear Regression and Random Forest models.
5. Compare MAE, RMSE, and R² on a held-out test set.
6. Review feature importance and generate an example prediction.

## Run Locally
Install packages:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook student_performance_prediction.ipynb
```

Keep `student_performance.csv` in the same folder, then run all cells.

## Results
Model metrics and charts are generated when the notebook is executed. Add your verified results here after running all cells.

## Limitation
This is a learning portfolio project based on synthetic data. It should not be used to make decisions about real students.
