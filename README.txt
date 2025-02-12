Sentiment Analysis on IMDB Movie Reviews

# Project Overview
This project performs sentiment analysis on the IMDB movie reviews dataset using Machine Learning models. 
The goal is to classify reviews as positive or negative using various preprocessing techniques, visualization, and model implementations.


- Ali Khalid (F2021266006)

# Key Features
1. Data Preprocessing
   - Handling missing values
   - Text cleaning (lowercasing, punctuation & URL removal)
   - Tokenization & Stopword removal
   - Lemmatization
   - TF-IDF feature extraction

2. Data Visualization
   - Sentiment distribution plots
   - WordCloud for frequent words
   - Review length distribution (before & after cleaning)

3. Machine Learning Models
   - K-Nearest Neighbors (KNN)
   - Support Vector Machine (SVM)
   - Decision Tree (DT)
   - Random Forest (RF)

4. Custom Model (Stacking)
   - Stacks SVM & Random Forest for improved predictions.

5. Performance Evaluation
   - Classification report & confusion matrices
   - Accuracy, Precision, Recall, F1-score comparison

# Results
| Model               | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| KNN               | 74.22%    | 72.94%    | 77.02% | 74.93%   |
| SVM               | 85.54%    | 84.93%    | 86.40% | 85.66%   |
| Decision Tree     | 71.88%    | 67.67%    | 83.79% | 74.87%   |
| Random Forest     | 81.75%    | 79.15%    | 86.22% | 82.53%   |
| Stacking Model    | 84.01%    | 84.02%    | 84.01% | 84.01%   |

# Project Structure
/Sentiment-Analysis-IMDB
│── data/
│   ├── train.csv
│   ├── test.csv
│
│── notebooks/
│   ├── Sentiment_Analysis.ipynb
│
│── src/
│   ├── preprocessing.py
│   ├── visualization.py
│   ├── models.py
│   ├── train.py
│
│── README.txt
│── requirements.txt
│── main.py
│── .gitignore

# How to Run
1. Install dependencies:
   pip install -r requirements.txt

2. Run the Jupyter Notebook:
   jupyter notebook

3. Run Python script:
   python main.py
