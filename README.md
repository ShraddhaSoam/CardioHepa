Heart-and-Liver-Disease-Prediction-using-Machine-Learning:

Thus preventing diseases has become more than necessary. Good data-driven systems for predicting diseases can improve the entire research and prevention process, making sure that more people can live healthy lives. This is where Machine Learning comes into play. Machine Learning helps in predicting the diseases, and the predictions made are quite accurate.

The project involved analysis of the diseases patient dataset with proper data processing. Then, different models were trained and and predictions are made with different algorithms KNN, Decision Tree, Random Forest,Logistic Regression etc
This is the jupyter notebook code and dataset I've used from Kaggle

I've used a variety of Machine Learning algorithms, implemented in Python, to predict the presence of heart and liver disease in a patient. This is a classification problem, with input features as a variety of parameters, and the target variable as a binary variable, predicting whether heart and liver disease is present or not.


Machine Learning algorithms used:

1. Logistic Regression (Scikit-learn)
2. K-Nearest Neighbours (Scikit-learn)
3. Decision Tree (Scikit-learn)
4. Random Forest (Scikit-learn)


Libraries Used -

Pandas (for data manipulation)
Matplotlib (for data visualization)
Seaborn (for data visualization)
Scikit-Learn (for data modeling)


Flask: The web application framework used for building the application.
MySQL: The database management system used for storing user information.
Flask-MySQLdb: A Flask extension used for MySQL database integration.
scikit-learn: A machine learning library used for building and deploying machine learning models.
Pickle: Python module used for serializing and deserializing Python objects.
HTML/CSS: Frontend technologies used for designing and styling the web pages.
Jinja2: Templating engine used for rendering dynamic content in HTML templates.


HEART DISEASE --

Column:

age         
sex         
cp          
trestbps    
chol        
fbs         
restecg     
thalach     
exang       
oldpeak     
slope       
ca          
thal        
target : field used to split the data into two sets (patient with heart disease, or no disease)
 


LIVER DISEASE -- 

Columns:

Age of the patient
Gender of the patient
Total Bilirubin
Direct Bilirubin
Alkaline Phosphotase
Alamine Aminotransferase
Aspartate Aminotransferase
Total Protiens
Albumin
Albumin and Globulin Ratio
Dataset: field used to split the data into two sets (patient with liver disease, or no disease)



Deployment Architecture:

The model was deployed locally (port: 5500). The backend part of the application was made using Flask and for the frotend part HTML and CSS was used. I have not focussed much on the frontend. The file "app.py" contains the entire flask code.


Accuracy achieved: 85% (Random Forest)

Dataset used:

Heart : https://www.kaggle.com/datasets/arezaei81/heartcsv

Liver : https://www.kaggle.com/datasets/uciml/indian-liver-patient-records



TECHNOLOGY USED:

Python, Jupyter Notebook, Flask, Numpy, Pandas, Seaborn, Scikit-learn, Matplotlib, Kaggle
# CardioHepa
