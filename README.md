# 📰 News Headlines Sentiment Analysis

## 📌 Project Overview

This project scrapes the latest news headlines from the Times of India website, stores them in a CSV file, and performs sentiment analysis using the VADER (Valence Aware Dictionary and sEntiment Reasoner) model from NLTK.

The objective is to classify news headlines as Positive, Negative, or Neutral based on their sentiment scores.

---

## 🚀 Features

- Web scraping using Requests and BeautifulSoup
- Extract latest news headlines
- Store scraped data in CSV format
- Perform sentiment analysis using NLTK VADER
- Generate a final CSV containing sentiment scores and sentiment labels

---

## 🛠️ Technologies Used

- Python 3.x
- Requests
- BeautifulSoup4
- Pandas
- NLTK (VADER)
- CSV

---

## 📂 Project Structure

```
News-Sentiment-Analysis/
│
├── Python Project.ipynb        # Jupyter Notebook
├── data.csv                    # Scraped news headlines
├── reviews_with_sentiment.csv  # Headlines with sentiment results
├── README.md
└── requirements.txt
```

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/news-sentiment-analysis.git
```

Move to the project directory:

```bash
cd news-sentiment-analysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

or

```bash
pip install requests beautifulsoup4 pandas nltk
```

Download the VADER lexicon:

```python
import nltk
nltk.download('vader_lexicon')
```

---

## ▶️ How It Works

### Step 1: Web Scraping

- Connects to the Times of India website.
- Downloads the webpage.
- Parses HTML using BeautifulSoup.
- Extracts the latest news headlines.

### Step 2: Save Data

The extracted headlines are saved into:

```
data.csv
```

### Step 3: Sentiment Analysis

Each headline is analyzed using VADER to generate:

- Positive Score
- Negative Score
- Neutral Score
- Compound Score
- Sentiment Label

### Step 4: Export Results

The final output is saved as:

```
reviews_with_sentiment.csv
```

---

## 📊 Sample Output

| Headline | Compound Score | Sentiment |
|----------|---------------:|-----------|
| Stock market hits record high | 0.72 | Positive |
| Heavy rainfall disrupts city life | -0.46 | Negative |
| Government announces new policy | 0.00 | Neutral |

---

## 📈 Applications

- News sentiment monitoring
- Media analytics
- Market trend analysis
- Public opinion analysis
- NLP learning projects

---

## ⚠️ Note

- The HTML structure of the Times of India website may change over time.
- If CSS classes are updated, the scraping selectors must also be updated.
- Respect the website's Terms of Service and robots.txt before scraping.

---

## 🔮 Future Enhancements

- Scrape multiple news websites
- Automate daily data collection
- Visualize sentiment using charts
- Build an interactive dashboard
- Store data in a SQL database
- Deploy as a web application using Streamlit or Flask

---

## 👨‍💻 Author

**Bhushan Sakhalkar**

Data Analyst | Python | SQL | Power BI | Excel | Machine Learning

---

## 📄 License

This project is intended for educational and learning purposes.
