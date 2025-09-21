# Gaussian Naive Bayes - Titanic Dataset

This project is a simple example of **supervised classification** using the **Gaussian Naive Bayes** algorithm from [scikit-learn](https://scikit-learn.org/).  

---

## 📂 Project Structure

- `gaussian_naive_bayes.ipynb` → Main Jupyter Notebook with all the code.  
- `original_dataset/Titanic-Dataset.csv` → Raw dataset used for training and evaluation.  
- `original_dataset/feature-analysis.csv` → Description of data and selected features. 
- `README.md` → Project documentation.

---

## 📊 Workflow

1. **Data preprocessing**  
   - Column renaming.  
   - Handling missing values.  
   - Converting categorical variables (`sex`, `embarkationPort`) into dummy variables. (Required for Gaussian Naive Bayes)  

2. **Train-test split**  
   - 80% training set and 20% testing set using `train_test_split`.  

3. **Model training**  
   - Training a `GaussianNB` classifier on the selected features.  

4. **Model evaluation**  
   - Accuracy score.  
   - Confusion matrix to analyze misclassifications.  

5. **Visualization**  
   - Confusion matrix heatmap using `seaborn`.