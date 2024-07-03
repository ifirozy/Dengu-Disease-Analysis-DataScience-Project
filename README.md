# Dengue Prediction and Analysis

# Overview
This project aims to analyze dengue fever data, identify key symptoms associated with dengue, and build a machine learning model to predict the likelihood of dengue infection based on the presence of specific symptoms. The project also explores various data visualizations and feature selection techniques to enhance the predictive model's accuracy.

# Data Description
The dataset includes various features related to dengue symptoms, patient demographics, and other relevant information. Key columns include:

dengue_or_not: Indicates whether the patient has dengue (1) or not (0).
dengue.servere_headche: Presence of severe headache (yes/no).
dengue.pain_behind_the_eyes: Pain behind the eyes (yes/no).
dengue.joint_muscle_aches: Joint and muscle aches (yes/no).
dengue.metallic_taste_in_the_mouth: Metallic taste in the mouth (yes/no).
dengue.appetite_loss: Appetite loss (yes/no).
dengue.addominal_pain: Abdominal pain (yes/no).
dengue.nausea_vomiting: Nausea and vomiting (yes/no).
dengue.diarrhoea: Diarrhea (yes/no).

# Key Findings
Symptoms Analysis: Severe headache, pain behind the eyes, and joint/muscle aches are significant indicators of dengue.
Predictive Modeling: Logistic Regression with Recursive Feature Elimination (RFE) identified the top 5 most predictive features, achieving an accuracy of X%, precision of Y%, recall of Z%, and an F1 score of W%.

Data Visualizations: Heatmaps and bar plots provided insights into symptom correlations and prevalence.

#Future Work
Advanced Models: Explore Random Forest, SVM, and deep learning models for improved accuracy.
Expanded Data: Collect and integrate more data, including environmental factors and patient demographics.
Real-World Implementation: Develop a real-time application for early dengue detection.

# Data Preprocessing:

Preprocess the dataset using the scripts in the scripts/ directory.
Encode categorical variables and scale numerical features. Handle the missing vallues.

# Feature Selection:

Use Recursive Feature Elimination (RFE) to identify the most predictive features.

# Model Training:

Train the logistic regression model using the preprocessed data and selected features.
Evaluate the model performance using accuracy, precision, recall, and F1 score.

# Visualizations:

Generate various plots to visualize data insights and model performance.

# Conclusion
This project demonstrates the potential of using machine learning for early dengue detection and highlights the importance of data-driven approaches in disease prediction and prevention. By leveraging advanced modeling techniques and continuously improving data collection efforts, we can develop more accurate and effective predictive models.
