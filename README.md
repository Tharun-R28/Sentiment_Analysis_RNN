# RNN-Based Sentiment Analysis 🎬

A Natural Language Processing (NLP) project that aims to classify movie reviews as **positive or negative** using a Recurrent Neural Network (RNN) and the IMDB Movie Reviews Dataset.

## 📌 Project Overview

Sentiment Analysis is a Natural Language Processing task that identifies the emotional tone of textual data.

In this project, I am working on developing a deep learning model that can understand movie reviews and classify them into two sentiment categories:

- **Positive (1)**
- **Negative (0)**

The project uses text preprocessing techniques and an RNN architecture to explore how deep learning can be applied to real-world text classification problems.

## 🎯 Objectives

- Understand and preprocess textual review data.
- Perform text cleaning and normalization.
- Convert text into numerical representations using TF-IDF.
- Develop an RNN-based sentiment classification model.
- Train and evaluate the model.
- Understand how recurrent neural networks process sequential text data.

## 📂 Dataset

**IMDB Movie Reviews Dataset**

The dataset contains movie reviews and their corresponding sentiment labels.

Expected columns:

| Column | Description |
|---|---|
| `review` | Movie review text |
| `sentiment` | Positive or negative sentiment |

Dataset source: [IMDB Dataset – Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

Download the dataset and place `IMDB Dataset.csv` in the project directory.

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- NLTK
- Scikit-learn
- PyTorch
- Matplotlib
- Jupyter Notebook

## 🔄 Project Workflow

### 1. Data Loading and Exploration
- Load the IMDB dataset using Pandas.
- Examine dataset dimensions and sample records.
- Check missing values.
- Remove duplicate records.

### 2. Text Preprocessing
The planned preprocessing pipeline includes:

- Converting text to lowercase.
- Removing URLs.
- Removing HTML tags.
- Removing punctuation.
- Removing stopwords.
- Performing stemming.

### 3. Text Vectorization
- Transform text into numerical features using TF-IDF.
- Prepare training and testing data.

### 4. RNN Model Development
- Build a Recurrent Neural Network using PyTorch.
- Define the loss function and optimizer.
- Train the model using the training dataset.

### 5. Model Evaluation
- Evaluate predictions on unseen test data.
- Measure classification performance.
- Analyse model results.

## 📁 Project Structure

```text
RNN-Sentiment-Analysis/
│
├── RNN_for_sentiment_analysis.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
└── dataset/
    └── IMDB Dataset.csv
```

## 🚧 Current Project Status

**In Progress**

Currently working on:
- Dataset exploration.
- Text preprocessing.
- Feature extraction.
- RNN implementation.
- Model training and evaluation.

Performance metrics and final results will be added after completing model training and testing.

## 🚀 Future Improvements

- Experiment with LSTM and GRU architectures.
- Improve text representation using word embeddings.
- Compare different deep learning architectures.
- Build an interactive sentiment prediction application.
- Improve model performance through hyperparameter tuning.

## 👨‍💻 Author

Tharun R

GitHub: Tharun-R28(https://github.com/Tharun-R28)

---

⭐ If you find this project interesting, feel free to explore the repository!

This project is developed for learning and practical exploration of Natural Language Processing and Deep Learning.