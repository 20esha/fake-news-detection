# fake-news-detection

🔹 Project Overview
This project aims to detect whether a news article is real or fake 
using Natural Language Processing (NLP) and Machine Learning techniques.

The model analyzes textual content and classifies news as 
REAL or FAKE based on learned patterns from historical data.


 🎯 Problem Statement
With the rapid spread of misinformation online, 
it is crucial to build automated systems that can detect fake news 
to prevent the spread of false information.



 🛠 Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Logistic Regression / Naive Bayes / PassiveAggressiveClassifier


📂 Dataset
- Dataset contains real and fake news articles
- Features include:
  - Title
  - Text
  - Label (REAL / FAKE)

(Source: Kaggle Fake News Dataset)



 🔍 Machine Learning Pipeline
1. Data Cleaning
2. Text Preprocessing
   - Lowercasing
   - Stopword Removal
   - Tokenization
3. Feature Extraction using TF-IDF
4. Model Training
5. Model Evaluation
6. Prediction


 📊 Model Performance
- Accuracy: XX%
- Precision: XX%
- Recall: XX%
- F1 Score: XX%




 📈 Key Insights
- TF-IDF significantly improved classification accuracy.
- PassiveAggressiveClassifier performed best among tested models.
- Fake news articles often contain exaggerated or emotionally charged language.


 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:
   pip install -r requirements.txt
3. Run:
   python main.py

 📁 Project Structure
Fake-News-Detection/
│
├── dataset.csv
├── model.pkl
├── main.py
├── preprocessing.py
├── requirements.txt
└── README.md




