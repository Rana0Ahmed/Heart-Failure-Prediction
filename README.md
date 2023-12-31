# Heart-Failure-Prediction
Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict a possible heart failure.

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR8f8M5V8nH3f7EnNX8e-Zpe19yM6DOBX2yGw&usqp=CAU" width="350">

### Attributes Information
- Age: age of the patient [years]
- Sex: sex of the patient [M: Male, F: Female]
- ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, - NAP: Non-Anginal Pain, ASY: Asymptomatic]
- RestingBP: resting blood pressure [mm Hg]
- Cholesterol: serum cholesterol [mm/dl]
- FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
- MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
- ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
- Oldpeak: oldpeak = ST [Numeric value measured in depression]
- ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: - flat, Down: downsloping]
- HeartDisease: output class [1: heart disease, 0: Normal]

### This Project includes:

- Import dependencies.
- Import Dataset from csv file and take a quick look.
- Data visualization with Correlation to gain some insights.
- Data processing on some columns.
- Feature selection and splitting data into train and test.
- Modeling using :
  - Decision Tree to get score around (0.84).
  - Random Forest to get score around (0.85).
- Hyperparameter Tuning to optimize Random Forest model using RandomizedSearchCV to get better score around (0.88).