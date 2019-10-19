# Medication compliance forecasting

To build a predictive model, you are provided a data set that contains details about patient and the prescription. 
Objective is to predict patient’s likelihood of adherence to a prescribed regimen. For that, information is provided both for patient and the prescription. Patient information include details like age, gender, medical history, cultural background etc. Details about the prescription are like Diet control advised, Exercise advised etc.

## Variables list:
![alt text](https://github.com/abhranil-datascience/PrescriptionAdherence/blob/master/Capture1.PNG)

Training data will be given with above mentioned variables including outcome variable (i.e. Adherence).
Your model’s performance will be evaluated on a test data set which will have the same variables.
Your model should give probability score for each patient and a prediction of whether patient will adhere to prescription or not (Yes / No). Please provide a function or definition to score the test data.

## Evaluation:
For each patient id in test set, you must predict if a patient is going to adhere to the prescribed regimen. Your model will be evaluated on precision and recall for both the outcomes. So, your code must include generation of confusion matrix for your predictions.
Example:<br />
![alt text](https://github.com/abhranil-datascience/PrescriptionAdherence/blob/master/Capture.PNG)
<br />
• Precision for Yes: 280/(280+1463)= 16.1%<br />
• Recall for Yes : 280/(280+42)= 87.0%<br />
• Precision for No: 18270/(18270+42)= 99.8%<br />
• Recall for No: 18270/(18270+1463)= 92.6%<br />


## Submission file format:
You need to upload final results and code in a zip file. It should have:<br />
a.) Result: In a csv file, adherence metric as yes or no for each patient with a probability score between 0 to 1.<br />
Sample output:<br />
patient_id, adherence, probability score
1001, yes, 0.99<br />
b.) Code in a file with appropriate file extension.<br />
c) A word document describing your approach to solve the above problem.
