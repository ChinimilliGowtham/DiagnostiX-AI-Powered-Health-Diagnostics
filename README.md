# 🩺 AI-Powered Health Diagnostics  

![Python](https://img.shields.io/badge/Built%20With-Python-3776AB?logo=python&logoColor=white)  
![Machine Learning](https://img.shields.io/badge/Powered%20By-Machine%20Learning-brightgreen)  
![Status](https://img.shields.io/badge/Status-Research%20Project-blue)  
![License](https://img.shields.io/badge/License-Academic-lightgrey)


Overview
This project is a research-based machine learning system that predicts potential diseases based on user-inputted symptoms and basic health parameters. By analyzing symptom patterns using classification algorithms, the model provides early health risk assessments along with recommended precautions.

✨ Key Features

🔍 Predicts diseases based on symptoms and health indicators (age, gender, blood pressure, cholesterol levels).

📈 Achieved 89% accuracy and 92% precision using Random Forest Classifier.

🛡️ Suggests precautionary steps based on predicted diseases.

🔬 Comprehensive model evaluation using Accuracy, Precision, Recall, ROC-AUC, and Confusion Matrix.


🛠️ Technologies Used

Python

Scikit-learn

Pandas

NumPy

Matplotlib / Seaborn (for evaluation graphs)


⚙️ Machine Learning Models Evaluated

Logistic Regression

Naive Bayes

Support Vector Machine (SVM)

Decision Tree

Random Forest (Selected Best)

📊 Dataset

Custom-built dataset containing 116 diseases, their symptoms, and recommended precautions.

Patient information fields: Age, Gender, Fever, Cough, Fatigue, Difficulty Breathing, Blood Pressure, Cholesterol Level.


📈 Results

Random Forest achieved the best performance:

Accuracy: 89%

Precision: 92%

High ROC-AUC Score and strong feature importance ranking.

🚀 How to Use

Clone the repository:

git clone https://github.com/yourusername/health-diagnostics.git

Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook to see model training, evaluation, and predictions.

📚 Future Work

Incorporate patient medical history and time-based symptom tracking.

Expand dataset size and diversity for improved generalization.

Explore real-time deployment using Flask APIs.

📄 License

This project is developed as part of a research-based academic project.

Feel free to explore and use it for learning and research purposes.

💬 Acknowledgments
Special thanks to faculty members and peer researchers for their guidance and feedback during the development of this project.

