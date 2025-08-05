#  Job Match Predictor using Machine Learning

This project uses a machine learning model to predict how well a candidate's resume matches a job description based on skill overlap.

##  Features
- TF-IDF vectorization of job/resume skills
- Resume simulation (to mimic partial matches)
- Logistic Regression classifier
- Model accuracy & evaluation metrics

##  Dataset
- Source: [Anonymized job listings]
- Columns: Job Title, Key Skills

##  How It Works
1. Load and clean job data
2. Simulate resume by randomly dropping some skills
3. Generate a "Fit Label" (0 or 1) based on overlap
4. Train and test the model
5. Evaluate accuracy and classification report

