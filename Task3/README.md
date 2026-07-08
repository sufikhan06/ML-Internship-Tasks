\# Customer Churn Prediction API



\## Run Locally



Install dependencies:



```bash

pip install -r requirements.txt

```



Run the application:



```bash

python app.py

```



API URL:



```

http://127.0.0.1:5000

```



Prediction Endpoint:



```

POST /predict

```



Example JSON Request:



```json

{

&#x20;   "gender":1,

&#x20;   "SeniorCitizen":0,

&#x20;   "Partner":1,

&#x20;   "Dependents":0,

&#x20;   "tenure":12,

&#x20;   "PhoneService":1,

&#x20;   "MultipleLines":0,

&#x20;   "InternetService":1,

&#x20;   "OnlineSecurity":1,

&#x20;   "OnlineBackup":0,

&#x20;   "DeviceProtection":1,

&#x20;   "TechSupport":1,

&#x20;   "StreamingTV":0,

&#x20;   "StreamingMovies":0,

&#x20;   "Contract":1,

&#x20;   "PaperlessBilling":1,

&#x20;   "PaymentMethod":2,

&#x20;   "MonthlyCharges":70.5,

&#x20;   "TotalCharges":850.0

}

```



Example Response:



```json

{

&#x20;   "prediction":0

}

```

