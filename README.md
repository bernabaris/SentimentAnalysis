# Sentiment Analysis

This project performs sentiment analysis on a dataset of Turkish product reviews, using multiple machine learning models. The goal is to classify reviews as positive, neutral, or negative.

## Steps

1. **Load Dataset**: The dataset is read using pandas and inspected for null values, data types, and basic statistics.

2. **Data Preprocessing**:
   - **Stopwords Removal**: Turkish stopwords are removed using NLTK.
   - **Punctuation Removal**: All punctuation is removed from the text.
   - **Lowercase Conversion**: All text is converted to lowercase.
   - **Emoji Removal**: Emojis are removed using regex.
   - **URL Removal**: Any URLs are removed using regex.

3. **Exploratory Data Analysis**:
   - Word clouds for positive and negative reviews.
   - Pie chart and bar chart visualizations for sentiment distribution.

4. **Feature Extraction**:
   - **TF-IDF Vectorizer**: Transforms the text data into numerical features, with a maximum of 2500 features.

5. **Train-Test Split**:
   - Data is split into training (70%) and testing (30%) sets.

6. **Model Training and Evaluation**:
   - Multiple models are trained on the preprocessed data:
     - K-Neighbors Classifier
     - Gradient Boosting Classifier
     - Random Forest Classifier
     - Multinomial Naive Bayes
     - XGBoost Classifier
     - Logistic Regression
     - Support Vector Machine (SVM)
   - **Evaluation**: Each model's accuracy score on the test set is computed and displayed in a summary table.

7. **Results**:
   - The models' accuracy scores are displayed, with SVM achieving the highest accuracy.
     
## Contributors
This project was developed in collaboration with my classmates Şevval. 🌼 

