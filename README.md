# Social_Media_Data_Analysis_DVA_2
# 📊 Multilingual Social Network Data Analysis using NLP & Machine Learning

---

## 📌 Project Overview

This project implements a **complete data analysis pipeline** for a synthetic Instagram-like social network dataset. It combines **Natural Language Processing (NLP), Machine Learning, Deep Learning, and Network Analysis** to process and analyze multilingual user-generated content.

The dataset consists of **500,000 simulated records** across English and multiple Indic languages, including user profiles, captions, engagement metrics, and social connections.

---

## 🎯 Objectives

- Analyze multilingual text data
- Perform feature extraction and vectorization
- Apply dimensionality reduction techniques
- Build classification models for language detection
- Visualize social network relationships
- Extract insights from large-scale data

---
## ⚙️ Key Steps

* **Data Generation** – Created large-scale multilingual dataset
* **Preprocessing** – Cleaned captions (removed noise like hashtags, mentions)
* **Exploratory Data Analysis (EDA)** - Language distribution analysis , Caption length statistics
* **Vectorization** – TF-IDF, Bag of Words, and BERT embeddings
* **Dimensionality Reduction** – PCA and t-SNE for visualization
* **Classification** – Logistic Regression, Naive Bayes, Random Forest, ANN
* **Prediction** – Language detection on new inputs
* **Graph Visualization** – Social network analysis using NetworkX

----

## 🧱 Dataset Description

Each record includes:

### 👤 User Profile
- User ID
- Username
- Location
- Followers & Following count

### 📝 Content Data
- Post ID
- Caption (Multilingual)
- Language label

### 🔗 Interaction Data
- Hashtags
- Mentions

### 🌐 Network Data
- Friend connections
- Suggested users

### 📊 Engagement Metrics
- Likes
- Comments
- Shares

---

## ⚙️ Methodology

### 🔹 Step 1: Data Generation
- Generated 500,000 synthetic records
- Included English + Indic languages

---

### 🔹 Step 2: Data Loading & Exploration
- Loaded JSON dataset
- Verified structure and sample data

---

### 🔹 Step 3: Exploratory Data Analysis (EDA)
- Language distribution analysis
- Caption length statistics
- Engagement metrics distribution
- Followers vs Engagement insights

---

### 🔹 Step 4: Visualization (Before Preprocessing)
- Language count plots
- Caption length distribution

---

### 🔹 Step 5: Text Preprocessing
- Removed URLs, hashtags, mentions
- Removed special characters
- Cleaned text for modeling

---

### 🔹 Step 6: Visualization (After Preprocessing)
- Compared text length before & after cleaning
- Observed noise reduction

---

### 🔹 Step 7: Feature Extraction

#### ✔ TF-IDF
- Captures importance of words

#### ✔ Bag of Words
- Frequency-based representation

#### ✔ BERT Embeddings
- Used multilingual BERT model
- Extracted semantic vectors

---

### 🔹 Step 8: Dimensionality Reduction

#### ✔ PCA
- Reduced feature dimensions

#### ✔ t-SNE
- Visualized clustering of languages

---

### 🔹 Step 9: Classification Models and Prediction

#### ✔ Machine Learning Models
- Logistic Regression
- Naive Bayes
- Random Forest

#### ✔ Deep Learning Model
- Artificial Neural Network (ANN)

- Tested models on new text inputs
- Predicted language labels

---

### 🔹 Step 11: Network Graph Visualization
- Built graph using NetworkX
- Visualized user connections
- Identified influential users using centrality

---

## 📈 Results

- High accuracy in language classification
- Clear clustering observed in embeddings
- Effective preprocessing improved model performance
- Network graphs revealed influential users

---

## 🛠️ Technologies Used

- Python
- NumPy, Pandas
- Scikit-learn
- TensorFlow / Keras
- Transformers (BERT)
- Matplotlib, Seaborn
- NetworkX
- NLTK

---
## 🎓 Mentor
P. Srikanth

🔗 GitHub: https://github.com/srikanth5

## 👩‍💻 Authors
J. Parna Sree

🔗 GitHub: https://github.com/Parnas16


