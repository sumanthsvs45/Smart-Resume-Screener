As a MentorBaba intern, your goal is to build a machine learning model that predicts whether a resume matches a job description. This exercise will give you hands-on experience with text processing, embeddings, and classification, while introducing practical HR-AI applications.

Background
Recruiters often spend hours screening resumes. Automating resume screening not only saves time but also ensures the right candidates are identified. This assignment exposes you to a real-world problem in AI for HR, while allowing creativity in your solution.

Instructions
Step 1 – Dataset Preparation
Create a small dummy dataset with 10–15 pairs of:
Job Description (JD) text
Resume text
Label (1 = Match, 0 = No Match)
Example:
JD: "Looking for a Python developer with experience in ML and AWS."
Resume: "Experienced Python engineer skilled in ML, cloud computing, and AWS."
Label: 1
Step 2 – Text Preprocessing
Clean the text by:
Lowercasing
Removing punctuation and special characters
Optional: removing stopwords
Convert the text into numerical representations:
TF-IDF, CountVectorizer, or simple embeddings
Step 3 – Model Training
Choose a classification model: Logistic Regression, Random Forest, or a simple Neural Network.
Train the model to predict whether a resume matches a JD.
Step 4 – Evaluation
Evaluate your model using:
Accuracy
Precision, Recall, F1-Score
Display a confusion matrix for clarity.
Step 5 – Prediction on New Data
Test your model with at least 2 new JD-resume pairs.
Show predicted match/no-match results.
Step 6 – Creative Add-On (Optional)
Build a simple dashboard (Streamlit/Flask) to:
Upload a JD and a resume text file
Output a match score (probability of match)
You can also visualize feature importance or similarities for extra learning.
