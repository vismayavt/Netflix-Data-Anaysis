#  Netflix Data: Cleaning, Analysis, and Visualization (2008–2021)

This project explores and analyzes Netflix's streaming content using data science and natural language processing (NLP) techniques. It includes data cleaning, exploratory visualizations, feature engineering, machine learning, and content description analysis.

---

## 📁 Dataset

- **Source:** Netflix Titles Dataset (Kaggle or similar source)
- **Original Range:** 1965 to 2021  
- **Filtered Range:** 2008 to 2021 (to focus on modern, relevant trends)
- **File Used:** `netflix_cleaned_2008_2021.csv`

---

## Data Cleaning Steps

1. Removed duplicates and rows with critical missing values
2. Converted date columns to datetime
3. Extracted year and month from `date_added`
4. Filtered records from 2008–2021
5. Handled complex fields like genres and duration

---

## Exploratory Data Analysis (EDA)

- **Content Type Distribution**: Movies vs. TV Shows
- **Top Countries**: Countries with most content
- **Genre Trends**: Most frequent genres
- **Content Added Over Time**: Year-wise growth
- **Top Directors**: Creators with the most titles
- **Word Cloud**: Most common words in movie titles

📁 Saved Visuals: `Netflix_EDA_Visuals.png`  
(Also available separately in `/plots` folder)

---

##  Feature Engineering & ML

- Extracted `num_genres` and `duration_min` features
- Encoded categorical variables (`rating`, `genres`, `type`)
- Built a simple **Random Forest Classifier** to predict content type
- Evaluated model using accuracy and classification report

---

##  NLP Analysis (Descriptions)

- Cleaned and tokenized text from `description` column
- Applied:
  - **TF-IDF** to extract top keywords
  - **LDA Topic Modeling** to group content thematically
  - **Sentiment Analysis** to detect tone (optional)
- Summarized findings in `Netflix_NLP_Insights.txt`

---

##  Advanced Visualization

Used **Plotly** for interactive plots:
- Duration vs Number of Genres (scatter)
- Country-wise heatmap (optional)
- Trends by rating/category

---

##  Tools & Libraries Used

- Python (Pandas, NumPy, Seaborn, Matplotlib, Plotly)
- Scikit-learn (ML models)
- NLTK / spaCy / Gensim (NLP)
- WordCloud
- Jupyter / VSCode

---


##  Author

**Vismaya V.T**  

---

## ✅ Future Work

- Build a content recommendation system
- Deploy interactive dashboard using Streamlit/Tableau
- Fine-tune NLP models for improved topic modeling
- Integrate with TMDB or IMDb APIs for richer metadata

---



