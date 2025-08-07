# Diabetes Prediction using Machine Learning

A project that predicts diabetes based on medical data using several ML algorithms.

## 🧠 Models Used
- Decision Tree
- Random Forest (best accuracy)
- Logistic Regression

## 📊 Results
- Accuracy: 89% (Random Forest)
- Evaluation metrics: precision, recall, confusion matrix

## ⚙️ Tools & Libraries
- Python, Pandas, scikit-learn, Seaborn
- Jupyter Notebook / Google Colab

## 📁 How to Run
1. Clone this repo
2. Install requirements: `pip install -r requirements.txt`
3. Open and run the notebook: `diabetes_prediction.ipynb`
4. Make sure to replace the path to the dataset CSV file if necessary.

### 🔧 Replace Dataset Path
If the dataset is not in the same directory, edit the following line in the notebook:

```python
df = pd.read_csv('/path/to/your/Healthcare-Diabetes.csv')
```

## 🔗 Dataset
- [Healthcare Diabetes Dataset (Kaggle) - originally from the National Institute of Diabetes and Digestive and Kidney Diseases]
  (https://www.kaggle.com/datasets/nanditapore/healthcare-diabetes)
