# 📰 News Article Classification (Fake/Real)

This project uses machine learning to classify news articles as **Real** or **Fake**. The goal is to help detect misinformation by analyzing the content of news articles.

## 📁 Project Structure

- `News_Article_Classification.ipynb`: Main Jupyter notebook containing the complete workflow (data preprocessing, visualization, model training, and evaluation).
- `data/`: Folder to store dataset files.
- `models/`: Folder to store saved machine learning models (if needed).
- `README.md`: Project documentation.

## 📊 Dataset

- **Name**: [Fake and real news dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- **Files Used**:
  - `Fake.csv`
  - `True.csv`
- **Columns**:
  - `title`, `text`, `subject`, `date`

## 🧹 Data Preprocessing

- Merged `Fake.csv` and `True.csv`
- Dropped irrelevant columns (e.g. `date`)
- Cleaned text (lowercasing, punctuation removal, stopword removal, etc.)
- Labeled data: `0` for Fake, `1` for Real

## 📈 Exploratory Data Analysis (EDA)

- Word count distribution
- Word clouds for Fake and Real news
- Most frequent words

## 🧠 Model Training

Used the following models for classification:

- Logistic Regression
- Naive Bayes
- Random Forest
- Support Vector Machine (SVM)
- (Optional) TF-IDF Vectorization

### ✅ Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
