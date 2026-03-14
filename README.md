# 🌍 PyClimaExplorer
### *Turning Climate Data into Insight*

Welcome to **PyClimaExplorer**, a premium, scientific-grade climate intelligence platform designed to transform complex geospatial data into actionable insights. Built for researchers, scientists, policy makers, and climate enthusiasts.

---

## 🏆 Hackathon Details
- **Hackathon Name:** Hack it Out
- **Team Name:** Next Gen Developers
- **Team Members:**
    - **Aryan Mishra** (Team Leader)
    - **Aditya Kumar Singh**

---

## ✨ Key Features

### 🛰️ Spatial Heatmap
Interactive 2D visualizations of climate variables across the globe. Explore anomalies and trends with high-precision mapping.

### 📈 Advanced Time Series
- **ML Forecast:** 5-step predictive analysis using linear regression.
- **Dual-Axis Comparison:** Compare two variables (e.g., Temperature vs. Precipitation) on synchronized axes.
- **Smoothing Controls:** Real-time application of Moving Average and Exponential Smoothing to filter noise.

### 🌍 3D Geospatial Globe
A stunning, interactive 3D representation of climate data, providing an intuitive perspective on global patterns.

### 🤖 AI-Powered Intelligence
- **Research Analyst:** AI-driven insights powered by LLMs (Groq/Llama) to interpret complex data patterns.
- **Scifi Analyst:** A futuristic projection and analysis mode for theoretical climate scenarios.

### ⚖️ Comparison & Analytics
- **Variable Comparison:** Side-by-side analysis of different climate metrics.
- **Power BI Suite:** Advanced analytical dashboards for deep data drilling.

### 📡 Data Acquisition & Story Mode
- **Acquisition:** Tools for fetching and ingesting verified NetCDF datasets.
- **Story Mode:** Narrative-driven data exploration to tell the story of our changing planet.

---

## 🛠️ Technology Stack
- **Core:** Python 3.12
- **Frontend:** Streamlit, Vanilla CSS (Premium UI/UX)
- **Data Processing:** Xarray, Pandas, Numpy, NetCDF4
- **Visualization:** Apache ECharts (via custom renderer), Plotly, Pydeck (3D)
- **Scientific Math:** Scipy (Linear Regression, Trend Analysis)
- **AI Integration:** Groq API (Llama models)

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- A `.nc` climate dataset (NASA MERRA-2 recommended)

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/py-climax.git
   cd py-climax
   ```

2. **Set up Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Environment Variables:**
   Create a `.env` file in the root directory and add your API keys:
   ```env
   GROQ_API_KEY=your_key_here
   ```

### Running the App
Launch the dashboard with a single command:
```bash
streamlit run app.py
```

---

## 🔬 Data Authenticity
PyClimaExplorer is optimized for **NASA MERRA-2** (Modern-Era Retrospective analysis for Research and Applications, Version 2).
- **Verified Source:** Goddard Earth Observing System (GEOS)
- **Data Integrity:** Native support for `.nc` (NetCDF) files with automated metadata extraction.

---

## 🛡️ License
Distributed under the MIT License. See `LICENSE` for more information.

---

Built with ❤️ by **Next Gen Developers** for **Hack it Out**.
