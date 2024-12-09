# Restaurant Feedback Analysis - Python

A complete pipeline project in Python that scrapes restaurant reviews from OpenTable, extracts structured insights using LLM-based prompt engineering, visualizes results via a GUI, and performs competitor analysis using time-series data.

---

## 🚀 Features

- Web scraping using Selenium & BeautifulSoup with full pagination support
- Structured extraction of restaurant name, reviews, ratings, and dates
- Prompt-based analysis of reviews to extract food and staff-related comments
- Removal of personal identifiable information (PII)
- Interactive dashboard (built in Streamlit/Flask) for review visualization
- Color-coded display of food vs staff feedback
- Competitor analysis with rating trends and time-series graphs

---

## 🛠 Technologies Used

- Python
- BeautifulSoup & Selenium (for web scraping)
- OpenAI API / LLMs (for prompt engineering)
- Pandas, JSON, CSV (for data processing)
- Streamlit / Flask (for GUI dashboard)
- Matplotlib / Plotly (for visualization)

---

## 📁 How to Run (VS Code / Jupyter Notebook)

- Clone or download the repository
- Open the project folder in VS Code or JupyterLab
- Make sure Python and Jupyter are installed:
```bash
pip install notebook
```
- Open the `.ipynb` file
- You can simply run all cells step-by-step (no compilation needed)
- Scraped reviews are already saved in a `.json` file — no need to scrape again unless required

---

## 🧠 Concepts Practiced

This project was part of an **AI / Data Analysis** course and applies several real-world concepts:

- Web automation and data collection using scraping tools
- Prompt engineering and secure LLM usage (avoiding hallucinations + PII)
- JSON/CSV data handling for structured outputs
- Full-stack GUI integration for search and review highlight
- Time-series comparison for business insights

---

## 👨‍💻 Author

Ehtisham Abid
