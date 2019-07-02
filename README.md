# Data Intensive project

## Cardiovascular disease

There are 3 types of input features:

Objective: factual information;
Examination: results of medical examination;
Subjective: information given by the patient.

Features:

  1. Age | Objective Feature | age | int (days)
  2. Height | Objective Feature | height | int (cm) |
  3. Weight | Objective Feature | weight | float (kg) |
  4. Gender | Objective Feature | gender | categorical code |
  5. Systolic blood pressure | Examination Feature | ap_hi | int |
  6. Diastolic blood pressure | Examination Feature | ap_lo | int |
  7. Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
  8. Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
  9. Smoking | Subjective Feature | smoke | binary |
  10. Alcohol intake | Subjective Feature | alco | binary |
  11. Physical activity | Subjective Feature | active | binary |
  12. Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

  All of the dataset values were collected at the moment of medical examination. 

### File structure

Link to Google Colab notebook: [Colab notebook](https://colab.research.google.com/drive/1XBRY3k1Qyy6rAXo3gb7G8ZKon0ekbSe_#scrollTo=OYr97n2DrgZP)  
Link to webapp: [cvdisease](https://cvdisease.herokuapp.com)
