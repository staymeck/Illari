# 📈 Illary - Automated Trading System with AI

## 📝 Description

This project is an automated trading system based on Artificial Intelligence. It uses multiple "experts" to analyze historical data, social media sentiment, and investment strategies. A final model will make buy or sell decisions based on these analyses.

## 🏗️ Project Structure

```
📂 illary -> Analysing historical data
|---📂 scraper             # Bot for fetching real-time data
|---📁 data                # Storage for historical data
├── 📁 models              # AI models for analysis
├── 📁 strategies          # Investment strategies
├── 📁 decision_engine     # Decision-making engine
├── 📁 scripts             # Scripts for data processing
├── 📄 README.md           # Project documentation
└── 📄 requirements.txt    # Project dependencies
```

## 🚀 Technologies

- **Python** (for data processing and AI)
- **TensorFlow / PyTorch** (for machine learning models)
- **NLTK / BERT** (for sentiment analysis)
- **Binance API / Yahoo Finance API** (for market data retrieval)
- **PostgreSQL / MongoDB** (for data storage)

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ai-trading-bot.git
   cd ai-trading-bot
   ```

2. Create a virtual environment and install dependencies:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows
   pip install -r requirements.txt
   ```

3. Configure your API credentials (e.g., Binance, Yahoo Finance) in a `.env` file:

   ```
   BINANCE_API_KEY=your_api_key
   BINANCE_SECRET_KEY=your_secret_key
   ```

4. Run the historical data collection script:
   ```bash
   python scripts/get_historical_data.py
   ```

## 📌 Next Steps

✅ Implement historical data collection.
✅ Develop the historical data analysis model.
✅ Integrate sentiment analysis.
✅ Build AI-based trading strategies.
✅ Develop the final decision-making engine.

---

Welcome to the project! 🎯🚀
