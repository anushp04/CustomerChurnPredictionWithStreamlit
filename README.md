# Customer Churn Prediction With Streamlit

Customer churn is the percent of customers that stopped using a company’s services/product during a particular time.

Lost customers mean a direct loss of revenue which is why it is important to understand the reason behind customers leaving the company. Customer churn is the most important metric to evaluate the performance of a company. From the point of view of the company, it is necessary to gain this information because getting new customers is generally more tedious and costlier than retaining old customers.It has become known that predicting churn is one of the most important sources of income for telecom companies. Hence, this project aimed to build a system that predicts the churn of customers in a telecom company.


The dataset used in this project is “Telco Customer Churn version 11.1.3+” data provided by the IBM Cognos Analytics team. It contains information about a telco company that provided home phone and Internet services to 7043 customers in California in Q3. It indicates which customers have left, stayed, or signed up for their service.

The reporistory contains details about the EDA processm Feature Extracting and Preprocessing steps, along with the implementation of ML models such as Logistic Regression, k Nearest neighbor, SVM, Random Forest, XGBoost, LightBoost, and Artificial Neural Networks.


IBM Customer Churn Prediction with Streamlit

Step 1: <br/>
conda create -n churn python=3.7 <br/>
conda activate churn <br/>
pip install -r requirement.txt <br/>

Step 2: <br/>
python preprocess.py

Step 3: <br/>
streamlit run modelHost.py

Step 4: <br/>
Select the kind of input you want to your mode! <br/>
![Screenshot (9013)](https://user-images.githubusercontent.com/14346621/145688575-11bf9a1f-9452-46db-a824-258508e618f1.png) <br/>
l i.e SMOTE, SCALIMG , PCA etc <br/>
<br/>

Step 5: <br/>
Select the model <br/>
![Screenshot (9014)](https://user-images.githubusercontent.com/14346621/145688600-7242160c-3e9d-40c4-8364-be0bf1b55005.png) <br/>
<br/>

Step 6 <br/>
Select Hyperparameters <br/>
![Screenshot (9015)](https://user-images.githubusercontent.com/14346621/145688626-9ced7468-881f-4e69-b8f1-b0293ab0ee4a.png) <br/>
<br/>

