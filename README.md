# Inflation-Forecasting-TimeSeries-LLM

The project **"UK Inflation Forecasting and Sentiment Analysis"** applies **Natural Language Processing (NLP) techniques** to predict inflation trends in the UK using social media data, particularly tweets.   

### **Key Steps of the Analysis:**  
1. **Data Preprocessing & Feature Engineering:**  
   - Cleaning text data by removing links, emojis, and irrelevant tags.  
   - Assigning a **Relevance Score** to tweets based on account credibility.  
   - **Bots removal** to ensure data reliability.  

2. **Sentiment Analysis:**  
   - Conducted using four different models: **finBERT, Vader, Word2Vec, and TextBlob**.  
   - Classification of tweets as **positive, negative, or neutral** to gauge public sentiment on inflation.  

3. **Forecasting Models:**  
   - **XGBoost, LSTM, and ARIMA** were used to predict inflation trends.  
   - **ARIMA (0,1,0) showed the best performance**, closely matching actual inflation values.  

4. **Experimental Approaches:**  
   - **Named Entity Recognition (NER)** to extract inflation-related numerical data from tweets.  
   - **Ask-to-Data with Llama-2**, where a Large Language Model (LLM) was prompted to predict inflation directly from textual data.  
   - The LLM approach was promising but limited by **GPU constraints**.  

### **Key Results:**  
- **Sentiment analysis correlated with inflation trends**, helping improve forecast accuracy.  
- **ARIMA outperformed machine learning models** (XGBoost, LSTM) in predicting inflation.  
- **LLMs provided reasonable predictions**, but large-scale analysis was restricted due to computational limits.  

This study demonstrates that **social media sentiment can be a valuable predictor of inflation** and that **NLP techniques enhance traditional forecasting methods**.  

A particularly **innovative aspect** of this research is the use of **Large Language Models (LLMs) for direct inflation prediction**. Instead of relying solely on structured numerical models, the LLM approach allows for **a more dynamic and intuitive analysis**, extracting insights directly from text data. While computational constraints limited large-scale implementation, this technique represents **a novel way to forecast economic trends** and could become a powerful tool with further advancements in hardware and model optimization.
