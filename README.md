# roman-urdu-cyber-abuse-detection
"Cyber Abuse Detection in Roman Urdu using Machine Learning"

This project aims to detect **cyber abuse and offensive language** in **Roman Urdu** text using **Machine Learning** and **Natural Language Processing (NLP)** techniques. It was developed as part of my **Machine Learning Internship Project**.

# Project Overview

With the rapid growth of social media, incidents of **cyber harassment, bullying, and offensive language** have also increased, particularly in informal languages such as **Roman Urdu**.  
This project presents a **machine learning-based approach** to automatically detect abusive comments from social media text.

The system processes real-world data, applies **NLP techniques**, trains multiple **ML models**, and compares their performance.  
A **web interface (Flask-based)** is also developed to allow users to test the model in real time.

# Dataset

The dataset consists of **5,000+ Roman Urdu comments** manually labeled as:
- **H** → Hate(Abusive)  
- **O** → Ordinary(Non-Abusive)  

You can access the dataset on Kaggle here:  
🔗 [Roman Urdu Cyber Abuse Dataset](https://www.kaggle.com/datasets/hassan7838/roman-urdu-cyber-abuse-dataset)

# Machine Learning Models Used

| Algorithm | Description | Purpose |
|------------|-------------|----------|
| Logistic Regression | Linear classifier for text classification | Baseline model |
| Naïve Bayes | Probabilistic model for text data | Fast and interpretable |
| SVM | High-performance classifier for complex data | Effective for NLP tasks |

# Evaluation Metrics

- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1 Score**

All models were compared visually using bar charts and graphs to highlight performance differences.

# Tools & Technologies

| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python |
| Environment | Anaconda, Jupyter Notebook |
| Libraries | NumPy, Pandas, Matplotlib, Scikit-learn, NLTK |
| Web Framework | Flask |
| Frontend | HTML, CSS |

## 🚀 How to Run the Project

1. Clone this repository  
   ```bash
   git clone https://github.com/<your-username>/roman-urdu-cyber-abuse-detection.git
   cd roman-urdu-cyber-abuse-detection
