# Survey-Data-Visualization-Project
# 🚀 Survey Data Visualization Project 🚀



---

## 📌 Project Overview

This project transforms survey data into **engaging and insightful visualizations** using Python. Leveraging the **Star Wars Survey dataset** from FiveThirtyEight, it creates:
- **Static Visualizations**: Bar charts, pie charts, and heatmaps saved as a PDF.
- **Interactive Dashboard**: A web-based dashboard saved as an HTML file for dynamic exploration.

The goal is to uncover patterns in fan behavior, movie preferences, and ranking correlations through clear, professional visuals.

### Dataset
- **Source**: [FiveThirtyEight Star Wars Survey](https://raw.githubusercontent.com/fivethirtyeight/data/master/star-wars-survey/StarWars.csv)
- **Details**: Responses from Star Wars fans and non-fans, including:
  - Whether they’ve seen any Star Wars films.
  - Fan status (fan vs. non-fan).
  - Rankings of the six Star Wars movies (1–6).
  - Character favorability ratings.
- **License**: Provided by FiveThirtyEight under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/).

---

## 📊 Visualizations

The project generates four key visualizations:
1. **Bar Chart**: Fan status by whether hoge respondents have seen any Star Wars films.
2. **Pie Chart**: Proportion of respondents identifying as Star Wars fans.
3. **Heatmap**: Correlation of movie rankings across Episodes I–VI.
4. **Bar Chart**: Average movie rankings by fan status, highlighting differences in preferences.

---

## 🛠️ Requirements

- **Python**: 3.8 or higher
- **Dependencies**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly`

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn plotly


survey-data-visualization/
├── star_wars_survey_visualization.py   # Main Python script
├── requirements.txt                    # List of dependencies
├── star_wars_survey_visualizations.pdf # Output: Static visualizations
├── star_wars_survey_dashboard.html     # Output: Interactive dashboard
└── README.md                           # This documentation


🚀 Getting Started

bash




git https://github.com/<SheSwarnikaMIshra>/survey-data-visualization.git
cd survey-data-visualization
2. Install Dependencies
bash




pip install -r requirements.txt
3. Run the Script
bash




python star_wars_survey_visualization.py
4. Explore Outputs
Static Visualizations: Open star_wars_survey_visualizations.pdf to view bar charts, pie charts, and heatmaps.
Interactive Dashboard: Open star_wars_survey_dashboard.html in a web browser to interact with the visualizations.
