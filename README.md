# CREDITCARD-FRAUD-DETECTION-SYSTEM-USING-PYTHON
## credit card fraud detection

- machine learning project to detect fraudulent transactions  
- uses logistic regression for classification  
- complete pipeline from data preprocessing to prediction  

---

## features

- automatic detection of time, amount, and target columns  
- data visualization using histogram, scatter plot, and heatmap  
- feature scaling using standardscaler  
- stratified train test split for imbalanced data  
- model training using logistic regression  
- evaluation using accuracy and classification report  
- confusion matrix visualization  
- model saving using joblib and pickle  
- sample prediction support  

---

## technologies used

- python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- joblib  
- pickle  

---

## project structure

- fraud_data.csv → dataset  
- fraud_detection.py → main code  
- fraud_model.joblib → saved model  
- fraud_model.pkl → saved model  
- README.md → documentation  

---

## workflow

- load dataset  
- clean column names  
- detect important columns automatically  
- perform exploratory data analysis  
- split dataset into training and testing  
- scale features using standardscaler  
- train logistic regression model  
- predict results  
- evaluate performance  
- save model  
- run sample prediction  

---

## model evaluation

- accuracy score is displayed  
- classification report includes  
  - precision  
  - recall  
  - f1-score  
- confusion matrix plotted  

---

## how to run

- install required libraries  
  - pip install pandas numpy matplotlib seaborn scikit-learn joblib  

- place dataset file  
  - fraud_data.csv  

- run the script  
  - python fraud_detection.py  

---

## sample prediction

- predicts whether transaction is fraud or normal  

- output:
  - ⚠️ fraud transaction  
  - ✅ normal transaction  

---

## future improvements

- use advanced models like random forest and xgboost  
- handle imbalance using smote  
- hyperparameter tuning  
- deploy using streamlit  

---

## author

- kalaiyarasan s  
- full stack python developer  

---

## support

- give a star ⭐ on github  
- fork and improve  
