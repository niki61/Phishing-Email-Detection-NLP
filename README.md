Phishing Email Detection System
📌 Project Overview
Phishing remains one of the most significant threats in cybersecurity. This project implements an automated detection system that utilizes Natural Language Processing (NLP) and Machine Learning to identify phishing attempts within email content.

By analyzing the body and subject of emails, the system classifies them as either Safe or Phishing, helping to mitigate risks like credential harvesting and financial fraud.

✨ Key Features
TF-IDF Vectorization: Converts raw text into a numerical matrix (Term Frequency-Inverse Document Frequency) to highlight suspicious keywords.

Ensemble Learning: Uses a Random Forest classifier to improve detection accuracy and reduce false positives.

Text Aggregation: Processes combined text fields (text_combined) to capture the full context of the email.

Model Comparison: Evaluates Decision Trees, Random Forest, and Naive Bayes for optimal performance.

🛠️ Technology Stack
Language: Python 3.x

Libraries: Scikit-Learn, Pandas, NumPy

Techniques: TF-IDF Vectorization, Supervised Classification

📊 Dataset
This project utilizes the Phishing Email Dataset sourced from Kaggle. It contains over 18,000 labeled email samples, categorized as:

0 (Legitimate): Standard professional and personal communications.

1 (Phishing): Deceptive emails designed to steal information.

🤖 Models Implemented
Multinomial Naive Bayes: A highly efficient probabilistic model specifically optimized for text classification.

Random Forest Classifier: An ensemble of decision trees that provides high accuracy and robust generalization.

Decision Tree Classifier: Offers clear decision paths for keyword-based classification.

🚀 How to Use
Clone the repo:

Bash
git clone https://github.com/YOUR_USERNAME/Phishing-Email-Detection-NLP.git
Install Requirements:

Bash
pip install pandas scikit-learn numpy
Run the Script:
Place your phishing_email.csv in the root directory and run:

Bash
python 003.py
📈 Performance
The results include a comparative analysis of accuracy scores across all three models, allowing for the selection of the most reliable detector for a production environment.
