# 🕵️ Crime Analysis in Los Angeles

A data analysis project that explores crime trends in Los Angeles using Python and popular data visualization libraries. This project dives into how crime patterns shifted **before**, **during**, and **after** the COVID-19 pandemic, using interactive and static charts, heatmaps, and geographic mapping.

---

## 📑 Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Visualization Highlights](#visualization-highlights)
- [Dependencies](#dependencies)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

---

## 🧭 Introduction

This project analyzes and visualizes crime data from Los Angeles, showcasing how incidents evolved across different time periods, especially surrounding the COVID-19 pandemic. It uses visual storytelling to provide insights into trends, frequency, and spatial distribution of crimes using heatmaps and time-based plots.

---

## ✨ Features

- 📊 Comparative visualizations (Before, During, and After COVID-19)
- 🗺️ Geographic heatmaps using **Folium**
- 📈 Trend lines, histograms, bar plots, and more
- 🔍 Insights on crime type distribution and time-based trends
- 🧼 Cleaned and processed large datasets with **Pandas** and **NumPy**
- 📍 Location-based clustering and hotspot detection

---

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/la-crime-analysis.git
   cd la-crime-analysis
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Usage

1. Make sure the dataset (e.g., `LA_crime_data.csv`) is placed in the project directory or update the path in the script accordingly.
2. Run the analysis script:
   ```bash
   python crime_analysis.py
   ```
3. Outputs such as charts and maps will be saved in the `outputs/` directory or displayed inline if run in a Jupyter Notebook.

---

## 🌐 Visualization Highlights

- **Time-Series Charts**: Analyze crime frequency over time and during key periods (COVID-related timelines).
- **Categorical Plots**: Crime types, time of day, locations, etc.
- **Folium Heatmaps**: Interactive crime hotspots across the LA map.
- **Subplots**: Combined views for side-by-side comparisons.

---

## 📦 Dependencies

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `folium`

Install all dependencies using:

```bash
pip install -r requirements.txt
```


## 🧪 Examples

You could include a few screenshots or a GIF of your output here for visual appeal:

- Crime Heatmap of LA
- Bar chart of crime types before COVID
- Line chart of crime frequency over time


---

## 🧯 Troubleshooting

- **Heatmap not displaying?** Ensure Folium is correctly installed and you are opening the HTML output in a browser.
- **Encoding issues with the dataset?** Try opening the CSV using encoding='latin1' or 'utf-8'.
- **Map markers not accurate?** Check if lat/lon columns are clean and not null.

---

## 👥 Contributors

- [Manish Sharma](https://github.com/manishsarmaa)

Feel free to open issues or pull requests to contribute!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
