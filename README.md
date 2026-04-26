# Social_Media_Data_Analysis_DVA_2

📊 Multilingual Social Network Data Analysis and Classification using NLP & Machine Learning
📌 Project Overview

This project focuses on designing and implementing a complete data analysis pipeline for a synthetic Instagram-like social network dataset. The pipeline integrates Natural Language Processing (NLP), Machine Learning, Deep Learning, and Graph Visualization to analyze multilingual user-generated content and interaction patterns.

The dataset contains 500,000 simulated records including user profiles, captions in multiple languages, engagement metrics, and network relationships.

🎯 Objectives

Process and analyze multilingual text data

Perform feature extraction and vectorization

Apply dimensionality reduction for visualization

Build classification models for language detection

Visualize social network relationships

Extract meaningful insights from large-scale data

🧱 Dataset Description

Each record in the dataset includes:
👤 User Profile Data
User ID
Location
Followers / Following count
📝 Content Data
Post ID
Caption (multilingual)
Language
🔗 Interaction Data
Hashtags
Mentions
🌐 Network Data
Friend connections
Suggested users
❤️ Engagement Metrics
Likes
Comments
Shares
⚙️ Methodology
🔹 Step 1: Data Extraction
Synthetic dataset created using Python
Generated 500,000 records
Included English + 10 Indic languages
🔹 Step 2: Data Loading & Exploration
Loaded JSON dataset
Verified dataset size
Inspected sample records
🔹 Step 3: Exploratory Data Analysis (EDA)
Checked dataset structure and missing values
Analyzed language distribution
Explored engagement metrics (likes, comments, shares)
Generated correlation heatmap
Studied caption length distribution
🔹 Step 4: Visualization (Before Preprocessing)
Visualized language distribution
Analyzed caption length distribution
🔹 Step 5: Text Preprocessing
Removed:
 URLs,Hashtags,Mentions and Special characters
Generated cleaned captions
🔹 Step 6: Visualization (After Preprocessing)
Compared text before and after cleaning
Observed reduction in noise and improved consistency
🔹 Step 7: Feature Extraction
✔ TF-IDF (Term Frequency - Inverse Document Frequency)
Captures importance of words in text
✔ Bag of Words (BoW)
Represents text as frequency vectors
✔ BERT Embeddings
Used multilingual BERT model
Extracted semantic embeddings (768-dimensional vectors)
🔹 Step 8: Dimensionality Reduction
✔ PCA (Principal Component Analysis)
Reduced dimensionality while preserving variance
✔ t-SNE (t-distributed Stochastic Neighbor Embedding)
Visualized clustering patterns in multilingual data
🔹 Step 9: Classification Models and Prediction
✔ Machine Learning Models
Logistic Regression
Naive Bayes
Random Forest
✔ Deep Learning Model
Artificial Neural Network (ANN)
Tested trained model on new input text
Successfully predicted language labels
🔹 Step 10: Network Graph Visualization
Built graph using NetworkX
Visualized:
User connections
Social interaction patterns
Identified influential users using centrality measures
📈 Results
Successfully processed large-scale multilingual dataset
Achieved strong accuracy in language classification
PCA and t-SNE visualizations showed clear clustering of languages
Network graphs revealed user connectivity and influence patterns
📊 Technologies Used
Python
NumPy, Pandas
Scikit-learn
TensorFlow / Keras
Transformers (BERT)
Matplotlib, Seaborn
NetworkX
🚀 How to Run
Install dependencies:
pip install transformers datasets evaluate jiwer rouge-score networkx matplotlib seaborn nltk scikit-learn
Run the notebook step by step
Enable GPU for better performance (recommended for BERT)
📌 Key Insights
Multilingual embeddings capture semantic meaning effectively
t-SNE provides better visualization for high-dimensional data
Random Forest performs well for text classification
Graph analysis helps identify influential users in the network
🏁 Conclusion

This project demonstrates how NLP, Machine Learning, and Graph Analytics can be combined to analyze large-scale multilingual social media data. The pipeline efficiently transforms raw data into meaningful insights, helping in understanding user behavior, language patterns, and network interactions.

👩‍💻 Authors
J. Parna Sree
🔗 GitHub: https://github.com/Parnas16
🎓 Mentor
P. Srikanth
🔗 GitHub: https://github.com/srikanth5
