Project Overview

This project performs Sentiment Analysis, Topic Modeling, and Customer Feedback Insights Visualization using NLP and Machine Learning techniques.
It analyzes customer feedback data to understand customer opinions, identify key issues, and generate actionable insights through an interactive Streamlit Dashboard.

The system classifies feedback into Positive, Negative, and Neutral sentiments and discovers major discussion topics such as billing issues, service quality, and customer support.

--Features--

>>Sentiment Analysis using:
VADER
TextBlob
BERT Transformers

>> Topic Modeling:
LDA (Latent Dirichlet Allocation)
BERTopic
KMeans Clustering

>>Data Visualization:
Sentiment distribution charts
Region & Service-wise analysis
Word Clouds

>> Machine Learning Model:
Random Forest sentiment prediction

>>Interactive Dashboard:
Built using Streamlit
Live data upload & analysis
Negative & Positive feedback insights

---Technologies Used---

Python
Pandas & NumPy
Scikit-learn
Transformers (HuggingFace)
VADER & TextBlob
BERTopic
Matplotlib & Seaborn
WordCloud
Streamlit
Ngrok / LocalTunnel
Google Colab

--- Project Workflow---

Data Upload & Cleaning
Sentiment Classification
Topic Extraction
Visualization & Analysis
Machine Learning Model Training
Interactive Dashboard Deployment

--- Output---

Dataset with sentiment labels
Topic clusters from feedback
Visual insight charts
Customer feedback dashboard
Sentiment prediction model report

-How to Run
--Install Dependencies
pip install pandas scikit-learn transformers textblob vaderSentiment bertopic matplotlib seaborn wordcloud streamlit pyngrok

---Run Sentiment Analysis Notebook
VOIS_Sentiment_analysis_feedback_addition.ipynb

----Run Streamlit Dashboard
streamlit run app.py

--- Dashboard Capabilities---
Upload customer feedback CSV
View sentiment distribution
Identify top negative issues
Analyze positive feedback themes
Region and service-based filtering

----Dataset Requirements----
Dataset should include columns like:
CustomerFeedback
CleanedFeedback
Region
Contract
InternetService
PaymentMethod
sentiment_label

---- Author----

CHIGATERI RAJESHA
GenAI & Data Analytics Enthusiast

---Future Improvements----
Real-time sentiment monitoring
Deep learning fine-tuned models
Automated report generation
Cloud deployment
