# 📊 Social Media Trend Analysis

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

A Python-based pipeline for analyzing social media trends using **Machine Learning** and **Time Series Forecasting**. This project performs sentiment analysis on tweets, visualizes trends over time, and predicts future sentiment using ARIMA and Prophet models.

---

## ✨ Features

- **Text Preprocessing** — Cleans tweets by removing URLs, mentions, hashtags, and special characters
- **Sentiment Analysis** — Uses VADER to compute compound sentiment scores
- **Time Series Modeling** — Trains ARIMA and Prophet models on daily aggregated sentiment
- **Interactive Visualizations** — Plotly-powered charts for sentiment trends and tweet volume
- **Mock Data Generator** — Built-in script to create synthetic data for testing

---

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/ARYA-5012/Social-Media-Trend-Analysis-.git
cd Social-Media-Trend-Analysis-
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Generate Mock Data (Optional)
If you don't have your own dataset:
```bash
python generate_mock_data.py
```

### 4. Run the Analysis
```bash
python main.py
```

*To use a custom dataset:*
```bash
python main.py --input data/your_tweets.csv
```

---

## 📁 Project Structure

```
Social-Media-Trend-Analysis/
├── data/                     # Input CSV files
├── src/
│   ├── preprocessing.py      # Text cleaning & column standardization
│   ├── sentiment.py          # VADER sentiment analysis
│   ├── models.py             # ARIMA & Prophet forecasting
│   └── visualization.py      # Plotly charting functions
├── main.py                   # CLI entry point
├── generate_mock_data.py     # Synthetic data generator
├── requirements.txt          # Python dependencies
└── README.md
```

---

## 📈 Sample Output

The pipeline generates interactive visualizations including:

| Chart | Description |
|-------|-------------|
| **Sentiment Over Time** | Daily average sentiment score trend |
| **Tweet Volume** | Number of tweets per day |
| **Prophet Forecast** | 30-day sentiment prediction with confidence intervals |

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python 3.9+ |
| NLP | NLTK, VADER |
| ML/Forecasting | scikit-learn, ARIMA, Prophet |
| Visualization | Plotly, Matplotlib, Seaborn |
| Data | Pandas, NumPy |

---

## 📋 Input Data Format

Your CSV file should contain at minimum:

| Column | Description |
|--------|-------------|
| `timestamp` or `date` | Date/time of the tweet |
| `text` or `Tweet` | Tweet content |

The pipeline auto-detects common column names and standardizes them.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👥 Team

- **ARYA-5012** 

---

<p align="center">
  Made with ❤️ for Data Science
</p>
