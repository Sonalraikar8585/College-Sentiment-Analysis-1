# College Sentiment Predictor – By College Name

## Project Description
This project predicts the overall sentiment of a college (Positive, Neutral, or Negative) based on reviews and feedback from students, faculty, and other stakeholders. By entering the college name, the system aggregates relevant data and predicts the general sentiment associated with that college.

This tool helps prospective students and stakeholders to quickly gauge public opinion about a college before making decisions.

---

## Features
- Predict overall college sentiment as **Positive**, **Neutral**, or **Negative**.
- Analyze reviews from multiple sources (students, faculty, public feedback).
- Simple interface: enter a college name and get sentiment results instantly.
- Visualization of sentiment distribution (optional).

---

## Technologies Used
- **Programming Language:** Python  
- **Libraries:** scikit-learn, pandas, numpy, matplotlib/seaborn, nltk (for NLP)  
- **Model:** Machine Learning Classifier (e.g., Logistic Regression, Random Forest, or Naive Bayes)

---

## How to Use
1. Clone the repository:
2.Create a virtual environment: python -m venv venv
3.Activate the virtual environment: .\venv\Scripts\activate
4.Install required Python packages:
pip install pandas numpy scikit-learn matplotlib seaborn streamlit
5.Train the machine learning model: python train_model.py
6.Run the Streamlit web app: streamlit run app.py
