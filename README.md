## Multiple Disease Prediction

Here I have used ML to predict 3 types of diseases i.e. 
- Diabetes Prediction
- Heart Disease Prediction
- Parkinson's Disease Prediction
___

### Task Performed for each disease predictions:
1. Cleaned the data.
2. Executed the Data Preprocessing and Feature engineering.
3. Performed Exploratory Data Analysis.
4. Used XGBClassifier, Random forest, SVC, GaussianNB & GradientBoostingClassifier Models for training purpose.
5. GaussianNB performed the best for Diabetes & Heart disease prediction with accuracy of 77.3% & 85.4% respectively.
6. Random forest performed the best in case of Parkinson's disease prediction with accuracy of 84%.
7. Ran locally using Streamlit.
___

### Run Locally

Clone the project
```
gh repo clone AnonymousSurya/Multiple_Disease_Prediction
```
Install dependencies

```
  pip install -r requirements.txt
```

Start the server

```
  streamlit run "D:\Projects\Multiple Disease Prediction System\multiple disease pred.py"
```
_P.S.: Change the file path as per your folder structure_

___
### Public hosting:

I have also deployed it publicly in the web.
Here is the link:
[Multiple Disease Prediction App](https://multiplediseasepreddeploymentapp-jl5drttyx4pshwqwzfrd9k.streamlit.app/)

_You can check [Multiple_Disease_Pred_Deployment_Streamlit](https://github.com/AnonymousSurya/Multiple_Disease_Pred_Deployment_Streamlit) repo for public web deployment_

___
Snapshot of the App:
![Screenshot (146)](https://github.com/AnonymousSurya/Multiple_Disease_Prediction/assets/76435009/62b832da-d31e-49d7-9b70-387bed3330f2)


