# Price Prediction Using Financial News Sentiment

This repository contains the Week 1 challenge of the 10 Academy Artificial Intelligence Mastery Program. The objective is to explore how financial news headlines influence stock price movements using natural language processing (NLP) and technical indicators.

## Project Objective

The goal of this project is to predict short-term stock price movements by analyzing the sentiment of financial news headlines and linking it with quantitative technical indicators. The work is designed to simulate a real-world data analyst or machine learning engineer's workflow in the financial domain.

We aim to:
- Perform Exploratory Data Analysis (EDA) on financial news data
- Compute technical indicators from historical stock market data
- Investigate the correlation between sentiment scores and daily stock returns
- Provide meaningful insights that could support investment decisions

## Project Structure

```bash
.
├── .vscode/              
├── .github/          
│       └── unittests.yml
├── notebooks/
│   ├── EDA.ipynb
│   └── technical_analysis.ipynb  
├── src/
│   └── __init__.py       
├── scripts/
│   └── __init__.py       
├── tests/
│   └── __init__.py      
├── requirements.txt      
├── README.md             
├── .gitignore   

```

---

##  Main Features

* **Task 1:** Financial news EDA, text preprocessing, and sentiment analysis using VADER
* **Task 2:** Stock technical indicators (SMA, RSI, MACD) and performance metrics visualization
* **Task 3:** Correlation analysis between daily news sentiment and daily stock returns (e.g., AAPL)
* Clean, modular, object-oriented design for reusable workflows
* Visual insights powered by `matplotlib` and `seaborn`


---

##  Getting Started

1. Clone the repository and install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
2. Place your data files into the `data/` directory as required by notebooks and modules.
3. Run the Jupyter Notebooks in the `notebooks/` folder for guided, task-based analysis.


---

##  Requirements

* Python 3.10+
* See `requirements.txt` for full dependency list

---
