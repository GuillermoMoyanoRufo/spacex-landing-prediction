## 🚀 SpaceX Falcon 9 Landing Prediction

### 🛠 Methodology

*   **Data Collection**: Technical data was extracted using the SpaceX API and supplemented with historical information obtained via web scraping from Wikipedia.
*   **Data Wrangling**: Data was transformed from JSON to DataFrames, specifically filtering for Falcon 9 missions and removing null values to ensure dataset quality.
*   **EDA (Visual & SQL)**: SQL queries and statistical visualizations were used to identify key trends, such as the relationship between flight number and success rate improvements.
*   **Interactive & Predictive Analysis**: 
    *   Performed geospatial analysis using Folium and developed interactive dashboards with Plotly Dash to segment success by payload and location.
    *   In the predictive stage, after evaluating models such as SVM, KNN, and Decision Trees, Logistic Regression proved to be the superior algorithm with an accuracy of 0.83.

### 📊 Summary of Results

*   **Success Trajectory**: SpaceX's success rate grew from 0.0 to 80% as flight experience increased.
*   **Orbit Performance**: Low-energy orbits (SSO/ES-L1) were identified as completely successful, while high-energy orbits (GTO) presented the greatest difficulty in recovery.
*   **Launch Sites**: The KSC LC 39A site stood out as the most reliable for heavy payloads exceeding 10,000 kg.
*   **Predictive Modeling**: Logistic Regression was confirmed as the best predictive model with 83% accuracy, proving particularly effective in identifying successful landings.

