##  Bank Loan Prediction System using Streamlit

## Steps:-

- Clone my repository.
- Open CMD in working directory.
- Run following command.

  ```
  pip install -r requirements.txt
  ```
- `Bank_Loan_Prediction.py` is the main Python file of Streamlit App. 
- To run app, write following command in CMD.

  ```
  streamlit run Bank_Loan_Prediction.py
  ```
- `Str_Loan_ML.ipynb` is the notebook file of the Data pre-processing & Machine Learning.
- `Loan_Data` contains the Dataset of this project.

## 
Installation of streamlit can get a bit back-breaking in windows. 
Even after the installation, the errors occur.
Easy way-> try to solve the errors one by one.
Firstly link all the servelets, from making the model to linking it with the  Bank_Loan_Prediction.py file.
-> One method is using Anaconda to launch new environment and then pip installing the servelet in it for the further use and running the project itself in it.

## my cmd window: 
!!!
(myenv) C:\Users\HP>cd C:\Users\HP\Dropbox\PC\Documents\Loan_Prediction_Streamlit_Application

(myenv) C:\Users\HP\Dropbox\PC\Documents\Loan_Prediction_Streamlit_Application>streamlit run Bank_Loan_Prediction.py

  You can now view your Streamlit app in your browser.

  Local URL: http://localhost:8501
  Network URL: http://192.168.0.101:8501
!!!
## @@@
1. Here, 'myenv' is my new Anaconda environment.
2. In it, move to the project folder.
3. Then install streamlit:
    'pip install streamlit'
  Then check installaion by typing 
    'streamlit --version'
4. To run the project, type
    'streamlit run Bank_Loan_Prediction.py'
5. Here, it will directly take you to the local host url. 
  If not, then go to the given local url from your browser. 
  Local URL-> its for your system locally.
  Where, Network URL-> it can connect about 5 devices that share the same network provider (ie you all 5 are connected to the same wifi).
 