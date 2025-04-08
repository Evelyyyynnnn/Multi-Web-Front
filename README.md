# 🧠 Multi-Function AI Web Assistant (Streamlit + OpenAI)

This is a multi-functional AI web app powered by **Streamlit** and **OpenAI GPT**, offering a suite of features from travel planning to stock dashboards and data visualization.

---

## 🧩 Features

- 🏖️ **Travel Assistant**  
  Input a city and get a fully detailed 3-day travel plan including attractions, food, and daily schedule. Powered by GPT.

- 📈 **Stock Forecast Dashboard**  
  Simulate and visualize stock trends with randomly generated time series.

- 📉 **Stock Price Charts**  
  Select multiple stocks (e.g. AAPL, GOOG, TSLA) and set date ranges to view historical stock prices using Plotly.

- 📁 **CSV Data Analyzer**  
  Upload a CSV file and automatically view it with basic statistical summaries.

- 📊 **Chart Visualizer**  
  Upload a CSV file and choose how to visualize it: bar chart, pie chart, line chart, or interactive Plotly charts.

- 🗺️ **Map Viewer**  
  Visualize location data directly on a map with coordinates (latitude & longitude).

   💬 **Chat History Viewer**  
  Store and view previous GPT answers in an interactive Q&A format.

---

## 🧪 Tech Stack

- Python 3.x
- [Streamlit](https://streamlit.io/)
- [OpenAI API](https://platform.openai.com/)
- Pandas, Numpy, Plotly, Matplotlib, yfinance

---

## 🚀 How to Run Locally

1. **Clone the repo**:

```bash
git clone https://github.com/yourusername/yourproject.git
cd yourproject

	2.	Install dependencies:

pip install -r requirements.txt

	3.	Set up your OpenAI API Key
Either hardcode it in app.py or manage it securely in .streamlit/secrets.toml:

openai.api_key = "your_openai_key"

	4.	Launch the Streamlit app:

streamlit run app.py



⸻

🌍 Deploy Online (Recommended)

You can deploy this project for free via Streamlit Community Cloud.
Just connect your GitHub repo and follow the prompts!

⸻

📷 Screenshots

Travel Planner	Stock Chart	CSV Analysis
		



⸻

🙌 Author

Made with ❤️ by Evelyn 
