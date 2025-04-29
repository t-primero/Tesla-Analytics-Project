# Tesla-Analytics-Project

Tesla Stock Moving Average Analysis

This project analyzes Tesla's historical stock prices using **20-day** and **50-day** simple moving averages (SMAs). The goal is to identify trend shifts and potential buy/sell signals using technical indicators.

Project Objectives

- Download and explore Tesla stock price data
- Calculate 20-day and 50-day moving averages
- Visualize price trends and MA crossovers
- Highlight periods of bullish or bearish momentum

Tools & Technologies

- Python
- Pandas
- Matplotlib & Seaborn
- Jupyter Notebook

Project Files

| File | Description |
|------|-------------|
| `Tesla_Project.ipynb` | Main notebook containing data analysis and visualizations |
| `tesla_moving_avg.py` | (Optional) Script version of the notebook |
| `tesla_plot.png` | (Optional) Static chart preview |
| `requirements.txt` | List of Python dependencies for easy setup |

Preview

![Tesla Stock MA Chart](tesla_plot.png)

> In this chart, we plot Tesla's closing price along with the 20-day and 50-day SMAs. Crossover points indicate possible trend reversals.

Key Takeaways

- Moving average crossovers can act as basic trading signals.
- 20-day MA crossing above 50-day MA → Bullish momentum
- 20-day MA crossing below 50-day MA → Bearish momentum

How to Run

1. Clone the repository or download this project folder
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
