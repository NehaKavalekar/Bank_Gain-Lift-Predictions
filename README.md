Bank Marketing Campaign Analysis using GAIN & LIFT Charts

🔍 Project Overview

This project analyzes a bank marketing dataset using Logistic Regression to predict whether a customer will subscribe to a term deposit. To evaluate the performance of the model in a business context, GAIN and LIFT charts are implemented.

These charts help measure how effectively the model identifies potential responders (i.e., customers who are likely to say “yes”) and whether the campaign can be optimized to reduce cost and improve conversion rates.


---

📁 Dataset

Source: UCI Machine Learning Repository

Attributes: Age, Job, Marital Status, Education, Default, Balance, Housing Loan, Personal Loan, Campaign Contact Counts, etc.

Target Variable: subscribed – Whether the customer subscribed to a term deposit (yes/no)



---

🧠 Model Used

Logistic Regression

Implemented using Scikit-learn

Model predicts the probability that a customer will respond positively to the campaign



---

📈 Business Metrics

✅ GAIN Chart

Measures how many actual responders (positives) are captured by the top X% of the predicted probability list

Helps identify the most valuable customers to target first


📈 LIFT Chart

Compares the performance of the model to random selection

LIFT > 1 means the model is better than random guessing



---

🛠 Tools & Technologies

Python

Jupyter Notebook

Scikit-learn

Pandas, NumPy

Matplotlib / Seaborn (for visualization)

Graphviz (for decision tree visualization)



---

📌 Key Learnings

Importance of evaluation beyond accuracy in imbalanced datasets

How Lift and Gain charts help in making better business decisions in marketing

Visualization of customer segmentation and targeting using ML
