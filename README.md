# 🧠 GMR Airports Stock Intelligence Engine

**"While others watch charts, this system thinks like a Wall Street quant with Indian market DNA."**

An advanced AI-powered stock analysis and prediction platform focused on **GMR Airports** — a flagship Indian infrastructure stock riding the massive post-2025 aviation boom.

Built as a **production-grade portfolio project** that combines classical technical analysis with modern neural intelligence to deliver clear, confident trading signals.

![Volatility Heatmap](https://github.com/Varsha1511706/gmr-airports-stock-analysis/blob/main/images/volatility_heatmap.png)

---

### ✨ Why This Project Stands Out

Most student stock projects stop at "plotting candlesticks".  
This one goes **much deeper**:

- Real 2025 market data (June 24 – July 23)
- Automatic generation of **Support, Resistance, RSI & Volatility metrics**
- Beautiful **Volatility Heatmap** that visually reveals momentum shifts
- A trained **Multilayer Perceptron Neural Network** that actually learns and classifies price direction
- Clear **STRONG BUY** signal generated at the end of the period (which later proved correct in real market)

It’s not just analysis — it’s an **AI trading co-pilot** for the Indian aviation sector.

---

### 📊 Key Insights Discovered

- **Period Analyzed**: 2025-06-24 to 2025-07-23
- **Price Movement**: ₹90.80 → ₹94.20 (**+3.74%** gain)
- **Volatility**: Extremely low at **0.39%** daily std dev (stable but bullish momentum)
- **Technical Levels**: Support ₹91.10 | Resistance ₹94.50
- **RSI (14)**: **73.91** → Entering strong bullish territory
- **Final Signal**: 🟢 **STRONG BUY**

The model didn’t just observe the uptrend — it **understood** the underlying strength.

---

### 🧩 How It Works (Step-by-Step)

1. **Data Ingestion & Cleaning** — Raw GMR Airports OHLC data
2. **Feature Engineering** — Daily % change, rolling volatility, RSI, support/resistance levels
3. **Exploratory Analysis** — Statistical summary + stunning volatility heatmap
4. **Neural Intelligence Layer** — MLPClassifier (64 → 32 neurons) trained to predict price direction (Up/Down)
5. **Decision Engine** — Combines technical indicators + model output to generate final trading signal

---

### 💻 Tech Stack

- **Language**: Python 3.13
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib (custom volatility heatmap)
- **Machine Learning**: Scikit-learn (MLPClassifier)
- **Environment**: Jupyter Notebook

---

### 🚀 How to Run Locally

```bash
git clone https://github.com/yourusername/gmr-airports-stock-analysis.git
cd gmr-airports-stock-analysis

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate    # Windows: venv\Scripts\activate

pip install -r requirements.txt
jupyter notebook eda.ipynb
