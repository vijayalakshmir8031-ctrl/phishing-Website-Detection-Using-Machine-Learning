#   phishing-Website-Detection-Using-Machine-Learning
🔐 Phishing Website Detection Using Machine Learning

📌 Project Overview  

Phishing websites are malicious websites designed to steal sensitive information such as usernames, passwords, banking details, and personal information.

This project uses Machine Learning to classify URLs as Phishing or Legitimate based on URL and website-related features.

🎯 Objective  

The main objective of this project is to build a machine learning classification model that can identify potentially phishing websites.

📊 Dataset

This project uses the PhiUSIIL Phishing URL Dataset from the UCI Machine Learning Repository.

Dataset: https://archive.ics.uci.edu/dataset/967/phiusil-phishing-url-dataset

The dataset contains URL and website-related features used for classification.

Target

- "0" → Phishing
- "1" → Legitimate

🤖 Machine Learning Algorithm

The project uses:

- Random Forest Classifier

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

🔄 Project Workflow

Dataset
   ↓
Data Loading
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Random Forest Classifier
   ↓
Model Training
   ↓
Prediction
   ↓
Evaluation

📈 Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

🚀 How to Run

1. Clone the repository

git clone YOUR_GITHUB_REPOSITORY_URL

2. Install required libraries

pip install -r requirements.txt

3. Download the dataset

Download the PhiUSIIL dataset from the UCI Machine Learning Repository and place the CSV file inside:

dataset/

4. Run the program

python src/phishing_detection.py

📌 Future Improvements

- Add more machine learning algorithms
- Compare model performance
- Add URL feature extraction
- Build a Streamlit web application
- Allow users to enter a URL and get a prediction
- Deploy the application online

👩‍💻 Author

Vijayalakshmi

B.Tech – Artificial Intelligence and Machine Learning
