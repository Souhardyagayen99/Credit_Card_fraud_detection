# Credit-Card-Fraud-Detection-ML-WebApp
# Dataset
link of dataset=https://www.kaggle.com/mlg-ulb/creditcardfraud
# Website 
link = https://credit-card-fraud-detection-tzcc.onrender.com

The datasets contains credit card transactions over a two day collection period in September 2013 by European cardholders. There are a total of 284,807 transactions, of which 492 (0.172%) are fraudulent.

The dataset contains numerical variables that are the result of a principal components analysis (PCA) transformation. This transformation was applied by the original authors to maintain confidentiality of sensitive information. Additionally the dataset contains Time and Amount, which were not transformed by PCA. The Time variable contains the seconds elapsed between each transaction and the first transaction in the dataset. The Amount variable is the transaction amount, this feature can be used for example-dependant cost-senstive learning. The Class variable is the response variable and indicates whether the transaction was fraudulant.

The dataset was collected and analysed during a research collaboration of Worldline and the Machine Learning Group of Université Libre de Bruxelles (ULB) on big data mining and fraud detection.

# Models
Applied various classification techniques like 
- Logistic Regression 
- LightGBM
- K Nearest Neighbors (KNN )
- Classification Trees
- Random Forest 
- SVM
- XGBoost Classifier

# Follow these steps --->
- For Run use Python 3.9.0 (download)
- python -m venv phishenv (create virtual environment)
- .\phishenv\Scripts\activate (activate venv)
- pip install -r requirements.txt (install required library)
- python app.py (run file)

 **Use Python 3.9.0**  
   Make sure you have Python 3.9.0 installed on your system.  
   👉 [Download Python 3.9.0](https://www.python.org/downloads/release/python-390/)

```
python -m venv phishenv
.\phishenv\Scripts\activate
pip install -r requirements.txt
python app.py
```


