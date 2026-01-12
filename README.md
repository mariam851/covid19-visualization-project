# COVID-19 Global Data Analytics & Geospatial Visualization

![COVID-19](fusion-medical-animation-rnr8D3FNUNY-unsplash.jpg)

## Project Overview
This project provides a comprehensive **Exploratory Data Analysis (EDA)** and **Geospatial Visualization** of the COVID-19 pandemic's global impact. By leveraging Python’s data science ecosystem, the project transforms raw epidemiological data into actionable insights, featuring interactive maps and animated time-series analysis to track the virus's spread.

---

## Tech Stack & Tools
* **Data Manipulation:** `Pandas`, `NumPy`
* **Geospatial Visualization:** `Folium` (Heatmaps, Circle Markers)
* **Interactive Graphics:** `Plotly Express` (Scatter Mapbox, Animated Choropleth)
* **Environment:** Google Colab / Jupyter Notebooks

---

## Key Features & Analytical Scope

### 1. **Geospatial Intelligence**
* **Interactive Heatmaps:** Utilized `Folium` to generate density maps, identifying global "hotspots" and infection clusters.
* **Scatter Mapbox:** Implemented high-resolution coordinate plotting to visualize cases at the city/province level.

### 2. **Temporal Trend Analysis**
* **Animated Time-Series:** Created dynamic Plotly animations that visualize the chronological progression of the pandemic across various continents.
* **Growth Metrics:** Comparative analysis of Confirmed vs. Recovered vs. Mortality rates.

### 3. **Data Preprocessing Pipeline**
* Cleaning and aggregating multi-source CSV data.
* Handling missing values and normalizing geographical coordinates for accurate mapping.

---

## Repository Structure
```text
├── data/               # Raw and processed CSV datasets
├── plots/              # Exported static and interactive visualizations
├── covid19.ipynb       # Core analytical notebook (Google Colab optimized)
└── README.md           # Project documentation
```

---

## Technical Highlights for Recruiters

* **Scalability:** The visualization pipeline is engineered to process and render large-scale time-series datasets efficiently, ensuring smooth performance even with thousands of daily global data points.
* **UX-Focused Design:** I prioritized **interactive charts** over static images. This allows stakeholders to "drill down" into specific country-level data, offering a granular view of the pandemic’s impact.
* **Data Integrity:** Implemented a rigorous data cleaning and validation layer. This ensures that latitudinal/longitudinal coordinates are perfectly aligned with global maps, eliminating geographical plotting errors.

---

## Tech Stack
* **Analysis:** Pandas, NumPy
* **Interactive Visuals:** Plotly Express
* **Geospatial Mapping:** Folium, Mapbox
* **Environment:** Jupyter / Google Colab

---

## How to Get Started

### Clone the Repository
```bash
git clone [https://github.com/yourusername/covid19-visualization.git](https://github.com/yourusername/covid19-visualization.git)
cd covid19-visualization
```

## Installation & Usage

### Install Dependencies
To set up the environment, run the following command to install the required data science libraries:
```bash
pip install pandas numpy plotly folium
```

---

### Running the Analysis
The project is optimized for both cloud and local environments. To generate the interactive geospatial maps:

* **Google Colab:** Upload the `.ipynb` file to your Drive for instant, zero-configuration cloud execution.
* **Jupyter Lab / Notebook:** Ensure all dependencies are installed, then execute the cells sequentially to build the data pipeline.

---

## Future Enhancements (Roadmap)
This project is part of an iterative development cycle. Planned updates include:

* [ ] **Real-time Data Integration:** Establishing automated pipelines to the *Open Disease Data API* for live monitoring.
* [ ] **Predictive Modeling:** Implementing **ARIMA** and **Facebook Prophet** algorithms to forecast future pandemic waves and growth trends.
* [ ] **Dashboard Deployment:** Transitioning the analytical backend into a production-ready **Streamlit** web application for end-user accessibility.

---

## Portfolio Note
This project is a cornerstone of my **Data Science portfolio**, specifically designed to showcase technical proficiency in:

1.  **Geospatial Intelligence:** Mastering advanced mapping, coordinate plotting, and layer visualization.
2.  **Data Integrity Management:** Implementing rigorous cleaning protocols to ensure precision in complex, high-dimensional time-series datasets.
3.  **Strategic Data Storytelling:** Developing the ability to translate raw, abstract numbers into clear, actionable visual insights for technical and non-technical stakeholders.
