## Diabetes Classification Using ANN
This project aims to build a predictive model using an Artificial Neural Network (ANN) to classify whether a patient is diabetic or not, 
based on diagnostic features from the PIMA Indians Diabetes Dataset. Tackling this health problem enables early detection and intervention, 
which is crucial for patient care.

## Project Overview:
The goal of this project is to build a machine learning model using an Artificial Neural Network (ANN) to classify whether a patient is diabetic or not, 
based on medical features such as: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age, Outcome. 
The dataset used was the Pima Indians Diabetes dataset, which contains medical data for 768 female patients of Pima Indian heritage.
The data was split into training and test sets, and the model was trained using a deep learning architecture that included callbacks like EarlyStopping and 
ModelCheckpoint to prevent overfitting and ensure the best model is saved.

## Model Prediction & Evaluation:
After training, predictions i made on the test set using the best model.
The model achieved an overall accuracy of approximately 69%.
The confusion matrix further showed the breakdown of true positives, true negatives, false positives, and false negatives,
helping assess how well the model distinguished between diabetic and non-diabetic patients. 
The classification report provided precision, recall, and F1-score for both classes, 
which are crucial in a medical setting where false negatives (predicting non-diabetic when the patient is diabetic) could have serious consequences.

## Conclusion & Impact:
The results suggest that the ANN model is reasonably effective in classifying diabetes based on patient health records.
In real-world healthcare settings, such predictive models can support early screening, 
helping medical professionals identify high-risk individuals for timely intervention and lifestyle management.
With further improvements—such as hyperparameter tuning, adding more data, or incorporating clinical features—this model can become an assistive tool in reducing undiagnosed
cases and improving patient outcomes in diabetes care.
