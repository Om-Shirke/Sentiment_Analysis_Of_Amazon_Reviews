# Sentiment_Analysis_of_Amazon_Reviews
</br>

## 📌 Project Description
This project focuses on analyzing customer sentiment in the US mobile phone industry to help a new smartphone manufacturer optimize its product development and marketing strategies using past Amazon review data. By leveraging customer reviews and metadata, the goal is to extract key insights into consumer preferences, competitor analysis, and market trends. The study involves data preprocessing, text analytics, and sentiment classification using Naïve Bayes to categorize reviews as positive or negative. Additionally, insights are visualized using a Tableau dashboard to highlight key factors influencing customer sentiment. These findings will enable data-driven decision-making, helping the company enhance brand positioning and increase market share.

## 🔧 Tech Stack  

- **Programming Language:** Python  
- **Libraries:**  
  - **Data Handling:** Pandas, NumPy  
  - **Visualization:** Matplotlib, Seaborn, Plotly  
  - **Text Processing:** NLTK (Tokenization, Lemmatization, Stemming), Regular Expressions (re)  
  - **Feature Extraction:** TfidfVectorizer  
  - **Model Training:** Scikit-learn (Naïve Bayes - MultinomialNB)  
- **Dataset Handling:** Gzip, Shutil  
- **Model Used:** Naïve Bayes (MultinomialNB) for Sentiment Classification  

## 🔍 Exploratory Data Analysis (EDA)  

- **Data Cleaning & Preprocessing:**  
  - Handled missing values and duplicate entries.  
  - Extracted relevant features from metadata and structured raw text data.  

- **Feature Engineering:**  
  - Tokenized and lemmatized text data for better analysis.  
  - Used TF-IDF vectorization to transform textual data into numerical format.  

- **Visualization:**  
  - Used Matplotlib, Seaborn, and Plotly to analyze sentiment trends and key market insights.  
  - Created visualizations for competitor analysis, customer sentiment distribution, and feature importance.  
## ⚡ Key Findings & Insights  

#### 🔹 Model Performance  
- **Test Dataset:**  
  - Accuracy: **89%**  
  - Sensitivity (Recall): **87%**  
  - Specificity: **82%**  
  - Area Under Curve (AUC): **90%**  

#### 📈 Model Improvements & Impact  
- The initial model without oversampling had **high sensitivity (0.95) but low specificity (0.59)**, meaning it identified positive cases well but struggled with negative cases.  
- **Applying oversampling** resulted in a more balanced dataset, improving the model's ability to correctly classify both positive and negative cases.  
- The refined model **outperforms the previous one**, offering better generalizability and prediction reliability.  

#### ✅ Business Insights  
- This model effectively **classifies sentiment in real-time**, making it useful for automating sentiment analysis tasks.  
- The high **AUC score (90%)** confirms the model's strong predictive power, ensuring **accurate sentiment classification** for new reviews.

## 🛠 How to Run
**Clone the repository:**
   ```bash
   git clone <https://github.com/Om-Shirke/Sentiment_Analysis_Of_Amazon_Reviews.git>
```
## 📈 Future Improvements  

- **Hyperparameter Optimization:** Use **GridSearchCV** or **RandomizedSearchCV** to fine-tune model parameters for better performance.  
- **Real-Time Sentiment Analysis:** Deploy the model for **live sentiment classification**, enabling businesses to monitor customer feedback in real-time.  
- **Feature Engineering Enhancements:** Experiment with **n-grams, word embeddings (Word2Vec, TF-IDF), and deep learning-based text representations** to capture more nuanced sentiments.  

## 📂 Project Structure  

| File Name                                         | Description  |
|--------------------------------------------------|--------------------------------------------------------------|
| `Merged_Dataframe.csv`                           | Comprehensive dataset containing Amazon customer reviews for sentiment analysis.  |
| `Negative_Features.csv`                          | Corpus of negative words used for sentiment classification.  |
| `Positive_Features.csv`                          | Corpus of positive words used for sentiment classification.  |
| `WEB_AND_SOCIAL_MEDIA_ANALYTICS_CAPSTONE_PROJECT.twbx`  | Tableau workbook with text analysis, visualizations, and key insights into customer sentiment and behavior.  |
| `WEB_AND_SOCIAL_MEDIA_ANALYTICS_Presentation.pptx` | Business presentation covering all findings, visualizations, and strategic recommendations for stakeholders.  |
| `WEB_AND_SOCIAL_MEDIA_ANALYTICS_PPT_RECORDING.mp4` | Recorded walkthrough explaining the methodology, key insights, and implementation strategies for business stakeholders.  |
| `README.md`                                     | Comprehensive project documentation.  |

## 📢 Credits & References

- **Project by:** Om Shirke

