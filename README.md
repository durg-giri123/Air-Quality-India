# Air-Quality-India
This project analyzes and visualizes air quality trends across major Indian cities using real-world datasets. With increasing environmental concerns, this project aims to uncover temporal and spatial patterns in air pollution through data cleaning, transformation, and interactive visualization techniques.

✅ Markdown Badge Block

---

### 🛠️ Tech Stack & Project Info

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Pandas](https://img.shields.io/badge/Library-pandas-150458)
![Seaborn](https://img.shields.io/badge/Visualization-seaborn-8A2BE2)
![Plotly](https://img.shields.io/badge/Interactive-Plotly-orange)
![GitHub Pages](https://img.shields.io/badge/Hosted-GitHub%20Pages-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)


🌐 Project Objective
✔️ To explore, analyze, and visualize air quality data of Indian cities to:

✔️ Understand pollutant trends over time.

✔️ Identify cities and seasons with critical air quality issues.

✔️ Present interactive and clear visualizations to aid public understanding and policymaking.



🔍 Features
✔️ Sourced and cleaned real-world air quality datasets.

✔️ Handled missing values, outliers, and performed data transformations.

✔️ Engineered features such as AQI category and pollutant concentration averages.

✔️ Created interactive charts and time series plots.

✔️ Interpreted findings through visual storytelling.



# 🛠️ Tech Stack
✔️ Tool/Library	Purpose
✔️ Python	Core programming language
✔️ Pandas	Data manipulation and analysis
✔️ NumPy	Numerical operations
✔️ Matplotlib	Data visualization (static plots)
✔️ Seaborn	Statistical visualizations
✔️ Plotly	Interactive charts and dashboards 🔥Used to create and host the live AQI chart via GitHub Pages |
✔️ Jupyter Notebook	Development & analysis interface



📊 Project Workflow (Based on Marking Rubric)
🔹 Phase 1: Data Collection & Preprocessing (30 Marks)
✔️ Identified and sourced air quality datasets (CPCB, Kaggle, OGD India).

✔️ Cleaned data and handled missing values.

✔️ Performed feature engineering (e.g., AQI category, pollutant trends).

✔️ Ensured data integrity and consistency.

✔️ Generated summary statistics and trends.


🔹 Phase 2: Visualization & Interpretation (20 Marks)
✔️ Selected appropriate charts (line graphs, heatmaps, bar charts).

✔️ Designed clear and aesthetically appealing visualizations.

✔️ Integrated interactive elements using Plotly.

✔️ Narrated findings with visual storytelling techniques.



## 📁 Folder Structure

```bash
air-quality-india/
├── data/               # Raw and cleaned datasets
├── notebooks/          # Jupyter Notebooks for analysis & visualization
├── src/                # Scripts for data preprocessing
├── visualizations/     # Output plots and interactive charts
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── .gitignore          # Ignored files
```

📈 Sample Insights
✔️ Delhi and Kolkata frequently recorded hazardous AQI levels during winter.

✔️ Significant AQI improvement during COVID-19 lockdown periods.

✔️ PM2.5 and NO2 were consistently dominant pollutants.



# 🚀 How to Run
1.Clone this repository:
git clone https://github.com/durg-giri123/air-quality-india.git

Navigate to the project folder:
cd air-quality-india

Install dependencies:
pip install -r requirements.txt

Open Jupyter Notebook:
jupyter notebook notebooks/air_quality_analysis.ipynb








# 🚀 Progress of Review 2

✅ Review 2: Data Visualization & Storytelling
This phase focuses on visualizing the air quality data to uncover patterns, anomalies, and seasonal variations in pollution levels across Delhi for the year 2023.


📌 Objective
To present the processed air quality data through clear, insightful, and aesthetically pleasing visualizations. Emphasis was placed on interactive storytelling using both static and dynamic (Plotly) charts.

📊 Key Visualizations
Visualization Type	Description
📈 Line Chart	Monthly AQI trend showing rise and fall in average pollution levels
📦 Box Plot	Monthly AQI distribution with spread, outliers, and medians
🔥 Bar Plot	Top 10 most polluted days in 2023 based on AQI
🌐 Interactive Line	Zoomable, hover-enabled line chart using Plotly for deeper exploration

All plots are saved in the visualization/ folder.

🌐 Interactive Chart (Hosted)
🔗 View Interactive AQI Trend – Delhi 2023

Built using Plotly: 
## 📈 Hosted Visualization

✅ Click below to interact with the AQI trend over time:

👉 [View Interactive Chart on GitHub Pages](https://durg-giri123.github.io/Air-Quality-India/interactive_aqi_trend.html)

📌 Built using Plotly & hosted via GitHub Pages


Hosted via GitHub Pages

Hover-enabled & zoomable

Aesthetically themed with dark mode


# ✅ Review 2 Highlights
✔️ Proper chart types selected for each insight
✔️ Clean, labeled, and color-tuned visual aesthetics
✔️ Interactive element using Plotly for deep-dive experience
✔️ README updated with hosted links and chart descriptions
✔️ Visualizations saved under visualization/ folder in organized structure

# 📁 File Structure (Updated)

```bash
Air-Quality-India/
├── notebooks/
│   └── Air-Quality-India.ipynb         # Final Review 2 notebook
│
├── visualization/
│   ├── monthly_aqi_trend.png           # Line chart: AQI trend over months
│   ├── monthly_aqi_boxplot.png         # Boxplot: AQI distribution by month
│   ├── top10_polluted_days_barplot.png # Top 10 polluted days barplot
│   └── interactive_aqi_trend.html      # Interactive Plotly chart (also hosted)
│
├── docs/
│   └── interactive_aqi_trend.html      # GitHub Pages source
│
├── README.md                           # Project overview and instructions
└── requirements.txt                    # Python dependencies
```


# 🔭 Future Enhancements
This project provides a foundational analysis of air quality trends. Potential future enhancements include:

📍 Incorporating more cities to build a comparative pollution profile across India

📅 Extending the dataset to include multi-year trends for long-term policy insights

📊 Adding pollutant-specific analysis (e.g., PM2.5 vs NO2 seasonality)

🗺️ Integrating geo-visualizations to plot AQI data on interactive maps

⚡ Deploying a real-time AQI dashboard using Streamlit or Dash

📲 Building a lightweight mobile app or chatbot interface to query live air quality

📚 Predictive modeling using machine learning for forecasting AQI spikes
