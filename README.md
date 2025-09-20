# IMDB Movie Reviews Sentiment Analysis

This project applies **Natural Language Processing (NLP)** and **Machine Learning** to perform sentiment analysis on the [IMDB Movie Reviews dataset](https://www.kaggle.com/datasets/valmetisrinivas/imdb-movie-reviews/data).

## 📌 Project Overview
- **Dataset**: IMDB reviews with 3 columns: `id`, `review`, and `label` (0 = negative, 1 = positive).
- **Goal**: Classify movie reviews as positive or negative.
- **Techniques**:
  - Text preprocessing: cleaning, stopwords removal, lemmatization.
  - Feature extraction with **TF-IDF**.
  - Machine Learning models: Logistic Regression, Random Forest, and Linear SVM.
  - Model evaluation with cross-validation, classification report, and confusion matrix.
  - Hyperparameter tuning using GridSearchCV.

## ⚙️ Workflow
1. **Exploratory Data Analysis (EDA)**:
   - Distribution of classes.
   - Distribution of review lengths.
   - Word clouds for positive and negative reviews.
2. **Preprocessing**:
   - Lowercasing, punctuation and URL removal.
   - Stopword removal.
   - Lemmatization.
3. **Modeling**:
   - Logistic Regression.
   - Random Forest.
   - Linear SVM.
   - GridSearchCV for hyperparameter tuning.
4. **Evaluation**:
   - Accuracy, F1-score, confusion matrix.
5. **Saving Model**:
   - Best model saved with `joblib`.

## 📊 Results
- Logistic Regression tuned with GridSearchCV performed best on validation and test sets.
- Provides balanced accuracy and F1-scores across positive and negative reviews.

## 🚀 Usage
Clone the repository and install requirements:

```bash
git clone https://github.com/yourusername/imdb-sentiment-analysis.git
cd imdb-sentiment-analysis
pip install -r requirements.txt

