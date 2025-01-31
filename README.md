# Sentiment Analysis Of Twitter Data using Machine Learning

## 📌 Project Overview
This project focuses on analyzing sentiment in Twitter data using **machine learning**. By leveraging **Natural Language Processing (NLP)** and **Logistic Regression**, the system classifies tweets as **positive or negative**. It automates sentiment analysis, making it faster and more efficient for businesses, researchers, and policymakers.

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Machine Learning Model**: Logistic Regression
- **Libraries & Frameworks**:  
- **Pandas, NumPy** – Data processing  
- **NLTK (Natural Language Toolkit)** – Text preprocessing (stopwords, stemming)  
- **Scikit-learn** – Model training & evaluation  
- **TfidfVectorizer** – Text-to-numeric conversion  
- **Pickle** – Model saving & loading
- **Platform**: Google Colab

## 📊 Dataset
The dataset used is **Sentiment140** from Kaggle, containing **1.6 million tweets** labeled as positive (1) or negative (0).

## 📈 Accuracy
 **Training Accuracy**: 79.6%
 **Testing Accuracy**: 77.8%

## 🔄 How This Project Works
1. **Data Collection**  
    The dataset is fetched from **Kaggle** and loaded into a Pandas DataFrame.  
2. **Data Preprocessing**  
    Remove unwanted characters, convert text to lowercase, and apply **stemming**.  
    Stopwords (like *the, is, in*) are removed for better text representation.  
3. **Feature Extraction**  
    Convert textual data into numerical form using **TF-IDF Vectorization**.  
4. **Model Training**  
    A **Logistic Regression model** is trained on the processed dataset.  
5. **Model Evaluation**  
    The model's accuracy is tested on unseen data.  
6. **Prediction**  
    Given a new tweet, the model predicts whether it is **positive or negative**.  
7. **Model Saving**  
   The trained model is saved using **Pickle** for future use.

## 👨‍💻 How to Run the Project
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/twitter-sentiment-analysis.git
   cd twitter-sentiment-analysis

2. Install dependencies:
   ```
   pip install -r requirements.txt
3. Run the Jupyter Notebook or Python script in Google Colab or a local environment.

## 🚀 Future Scope
- **Enhance accuracy using Deep Learning models (LSTMs, BERT, etc.)**
- **Expand dataset to include neutral tweets for multi-class classification**
- **Deploy as a web-based sentiment analysis tool**
- **Support real-time Twitter sentiment analysis with Twitter API**
