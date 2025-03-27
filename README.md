# Shopee App Review Sentiment Analysis

## 📌 Project Overview
This project focuses on analyzing user sentiment towards the Shopee app based on reviews from the Google Play Store. The pipeline consists of three main components:

1. **Review Scraping** – Extracting user reviews from the Google Play Store.
2. **Sentiment Analysis & Insights** – Analyzing and visualizing sentiment trends to understand user feedback.
3. **Sentiment Inference** – Applying machine learning models to classify sentiment (Positive, Neutral, Negative).

By leveraging natural language processing (NLP), this project helps businesses and researchers gain insights into user experiences and improve app performance based on feedback.

---

## 🛠 Project Structure
The project consists of the following Jupyter Notebook files:

- **`Reviews_Scraping.ipynb`** – Web scrapes user reviews from the Google Play Store.
- **`ShopeeReviewSentiment.ipynb`** – Analyzes and visualizes sentiment trends and key insights.
- **`Inference.ipynb`** – Applies sentiment analysis using machine learning models.

---

## 🔧 Requirements
To run this project, ensure you have the following dependencies installed:

```bash
pip install pandas numpy requests google_play_scraper selenium scikit-learn matplotlib seaborn
```


---

## 📂 How to Use
1. **Scrape Reviews**
   - Run `Reviews_Scraping.ipynb` to collect Shopee app reviews from the Google Play Store.
   - Ensure proper setup for googleplay scraping.

2. **Analyze and Visualize Results**
   - Use `ShopeeReviewSentiment.ipynb` to generate insights, visualize trends, and extract meaningful conclusions from user feedback.

3. **Run Sentiment Inference**
   - Execute `Inference.ipynb` to classify sentiment (Positive, Neutral, Negative) using a trained NLP model.
---

🤖 Machine Learning Models & Performance

We experimented with three different models for sentiment classification:

| Model  | Accuracy  | Split Ratio | Feature Type |
|----------|----------|----------|----------|
| LSTM + Embedding (80/20)   | 94.38% | 80/20 | Word Embedding |
| SVM + TF-IDF (80/20)   | 93.35% | 80/20 | TF-IDF |
|RF + TF-IDF (70/30)   | 90.67% | 70/30 | TF-IDF |

🔹 LSTM with Word Embedding achieved the highest accuracy (94.38%), making it the best choice for this task.

🔹 SVM with TF-IDF also performed well (93.35%), providing a strong baseline model.

🔹 Random Forest with TF-IDF had the lowest accuracy (90.67%), but still produced reasonable results.

Further optimization and hyperparameter tuning can be explored to enhance model performance.

## 📊 Key Features
✅ Automated review scraping from the Google Play Store  
✅ Machine learning-based sentiment analysis  
✅ Data visualization for understanding user feedback trends  
✅ Easy-to-use workflow with Jupyter Notebooks  

---

## 📌 Future Improvements
- Expand the dataset for better generalization.
- Improve model accuracy with fine-tuned transformers.
- Deploy the model as an API for real-time sentiment analysis.
- Enhance visualization with interactive dashboards.

---

## 🤝 Contribution & Support
Feel free to contribute by improving the code, fixing bugs, or optimizing the ML model. If you encounter issues, open an issue or contact the project maintainer.

🚀 **Happy Coding!**

