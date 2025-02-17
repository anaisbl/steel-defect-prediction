# Kaggle Playground Series - Steel Plate Defect Prediction

## Project Overview
This project is the final Continuous Assessment for the course "Programming with Big Data (PROG9813)" as part of the Data Science program (TU059) at TU Dublin. I participated in a Kaggle Playground Series competition, where the task was to predict steel-plate defects using machine learning models.

### Task Description
- Developed a classifier to identify various **defect categories** in steel plates.
- Submissions were evaluated using the **Area Under the ROC Curve (AUC-ROC)** for each defect type.
- The final score was an average of AUC-ROC values across all categories.

### Performance & Ranking
- Achieved an **AUC-ROC score of 0.86375**.
- Ranked in the **65th percentile**, placing **1443rd out of 2199 participants**.
- The top competitor achieved a score of **0.89782**.

### Technologies Used
- **PySpark**: Distributed computing framework for large-scale data processing.
- **Python**: Core programming language.
- **Jupyter Notebook**: Development environment.
- **MLlib (Spark's Machine Learning Library)**: Model training and evaluation.
- **Pandas & NumPy**: Data preprocessing and manipulation.
- **Matplotlib & Seaborn**: Data visualization.

### Project Structure
This repository contains **five Jupyter Notebook files**, each covering a different stage of the workflow:
1. **Cleaning Data** - Preprocessing and handling missing values.
2. **Quality Checking Data** - Validating data consistency and integrity.
3. **Model Creation** - Implementing machine learning models using PySpark MLlib.
4. **Model Tuning** - Hyperparameter optimization and performance evaluation.
5. **Final Predictions** - Generating predictions and submitting results.

### Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/steel-defect-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd steel-defect-prediction
   ```
3. Start a PySpark session:
   ```python
   from pyspark.sql import SparkSession
   spark = SparkSession.builder.appName("SteelDefectPrediction").getOrCreate()
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Run the notebooks sequentially to explore data processing, model training, and evaluation.

### Future Improvements
- Experiment with **ensemble learning** to improve predictive accuracy.
- Utilize **deep learning approaches** such as CNNs for defect detection.

---
Feel free to contribute or suggest improvements by opening an issue or pull request. 🚀

