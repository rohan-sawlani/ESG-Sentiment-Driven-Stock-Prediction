# ESG Sentiment-Driven Stock Price Prediction

This project investigates the relationship between sentiment extracted from ESG (Environmental, Social, and Governance) reports and short-term stock price movements for publicly listed US companies. The analysis leverages Natural Language Processing (NLP) techniques and financial time-series modeling to uncover whether ESG disclosures can serve as predictive indicators for stock performance.

---

## 📌 Objective

- To quantify the sentiment in ESG reports and assess its influence on subsequent stock price fluctuations.
- To explore the utility of ESG narrative tone as an early signal for financial decision-making.

---

## 📊 Dataset

- **ESG Reports:** Publicly available ESG disclosures of major US-based companies (e.g., from SEC EDGAR, company websites).
- **Stock Price Data:** Historical daily price data obtained using financial APIs such as Yahoo Finance.

---

## 🔍 Methodology

1. **Text Preprocessing:**
   - Tokenization, stopword removal, lemmatization
   - Removal of non-informative sections (boilerplate legal text)

2. **Sentiment Analysis:**
   - Applied both rule-based (e.g., VADER) and transformer-based models (e.g., BERT) to score document sentiment
   - Normalized sentiment over time to identify trends and shocks

3. **Financial Analysis:**
   - Time-aligning ESG sentiment scores with daily stock returns
   - Lag correlation, rolling averages, Pearson coefficient
   - Linear regression and visualizations to analyze predictiveness

---

## 📈 Key Results

- Discovered statistically significant correlations between dips in ESG sentiment and short-term negative price movements for select companies.
- Models incorporating ESG sentiment outperformed baseline return predictors by ~18% (based on classification accuracy).
- Demonstrated that ESG disclosures, when analyzed for sentiment, offer informative signals for short-horizon investment strategies.

---

## 🧠 Technologies Used

- Python, Pandas, NumPy
- NLTK, spaCy, VADER, HuggingFace Transformers
- Matplotlib, Seaborn
- Yahoo Finance API / yfinance

---

This project was developed as part of an undergraduate research initiative under the guidance of **Prof. Himanshu Yadav** at IIT Kanpur.

- **Rohan Sawlani** – [GitHub](https://github.com/rohan-sawlani)
- **Shrasti Dwivedi** – [GitHub](https://github.com/its-shrasti)

> For queries or collaborations, feel free to reach out via email or GitHub.


