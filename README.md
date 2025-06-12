# Activity-Level-Prediction-Using-Fitness-Tracker-Data
This study examines the application of machine learning to classify user activity levels using fitness tracker data. The dataset includes one million records with features such as steps, heart rate, sleep hours, active minutes, workout type, weather, and mood. A pipeline was developed
involving data preprocessing, feature engineering, SMOTE-based class balancing, and model evaluation through cross-validation. Four
supervised learning models such as Random Forest, Logistic Regression, K-Nearest Neighbors, and XGBoost were trained and compared. Overfitting
was a key challenge, largely due to overreliance on the steps feature, which led to inflated accuracy and label leakage. To mitigate
this, a composite activity level was engineered by combining normalized steps, heart rate avg, and active minutes, resulting in a
more informative target variable. Models trained on this revised label showed enhanced generalization and better class-wise performance, with
ensemble methods achieving the highest macro F1-scores. Evaluation metrics, including accuracy, precision, recall, and F1-score, were used to
assess the models under both original and engineered labeling strategies. Overall, the findings underscore the importance of robust label
construction and diverse feature sets in developing effective systems for behavioral data analysis, highlighting the potential of fitness tracker
data for personalized health monitoring and lifestyle interventions.

