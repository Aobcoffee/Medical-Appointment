# Medical Appointments Dataset - Predicting No-show Outcome
  This project utilizes a dataset imported from Kaggle [https://www.kaggle.com/datasets/joniarroba/noshowappointments]. 
  \
  \
  The dataset consists of 14 unique variables: "PatientID", "AppointmentID", "Gender", "ScheduledDay", "AppointmentDay", "Age", "Neighbourhood", "Scholarship", "Hipertension", "Diabetes", "Alcoholism", "Handicap", "SMS_received", and "No-show". The "No-show" variable will be used as the dependent variable and the predicting variable, while the remaining variables will serve as independent variables.


  
## Project Overview
In this project, we apply machine learning techniques to predict the "No-show" outcome in a medical appointments dataset. The goal is to determine whether a patient will show up for their medical appointment based on the features provided in the dataset.

## Library Requirements
This project used numpy and pandas to manage the datasets, and use pyplot and seaborn to visualize the data.

```
import pandas as pd
import numpy as np
import seaborn as sns
from matplotlib import pyplot as plt
```
