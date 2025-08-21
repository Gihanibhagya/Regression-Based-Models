📘 Machine Learning Model Evaluation – Colab Notebook

 🚀 Overview

This Google Colab notebook demonstrates the process of training, evaluating, and comparing multiple machine learning models.
The goal is to **analyze model performance** using metrics such as RMSE and R², and generate a final summary table with results.

 🛠 Features
 
Data preprocessing and splitting (train/test sets).
Training models such as:

  * Linear Regression
  * Decision Tree
  * Neural Network (MLPRegressor)
  * XGBoost
  * LightGBM
  * PyTorch-based models
 Evaluation using metrics: RMSE, R² Score.
 Results combined into a single Pandas DataFrame for comparison.
 Export final results to CSV/Excel.

📂 Project Structure

Notebook: Contains all code cells for data loading, training, evaluation, and saving results.
Outputs: A final CSV/Excel file (`final_model_results.csv`) summarizing model performance.

⚙️ Requirements

The following Python libraries are required:

```bash
pandas
numpy
scikit-learn
xgboost
lightgbm
torch
matplotlib
```

If using Colab, install missing dependencies with:

```python
!pip install xgboost lightgbm torch
```

▶️ How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Upload your dataset or connect Google Drive if needed.
3. Run cells step by step:

   * Data preprocessing
   * Model training
   * Evaluation
   * Results combination and export
4. Download the generated `final_model_results.csv` for further analysis.

📊 Example Output

A combined results table like:

| Model             | RMSE | R²   |
| ----------------- | ---- | ---- |
| Linear Regression | 12.5 | 0.85 |
| Decision Tree     | 10.8 | 0.88 |
| XGBoost           | 9.5  | 0.91 |
| LightGBM          | 9.2  | 0.92 |


