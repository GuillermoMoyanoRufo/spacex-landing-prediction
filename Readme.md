## 🚀 SpaceX Falcon 9 Landing Prediction

### 🛠 Metodología (Methodologies)

1. **Data Collection**: Extracción de datos técnicos mediante la [SpaceX API](github.com) y suplementada con técnicas de *web scraping* desde [Wikipedia](en.wikipedia.org) para obtener registros históricos.
2. **Data Wrangling**: Transformación de JSON a DataFrames, filtrado exclusivo de misiones **Falcon 9** y limpieza de valores nulos para garantizar la integridad del dataset.
3. **EDA (Visual & SQL)**: Uso de consultas en [SQL](www.sqlite.org) y gráficos estadísticos para identificar tendencias clave, como la correlación entre el número de vuelo y la tasa de éxito.
4. **Interactive & Predictive Analysis**: 
   - Análisis geoespacial con [Folium](python-visualization.github.io) y dashboards interactivos en [Plotly Dash](dash.plotly.com).
   - Evaluación de modelos de Machine Learning (**SVM, KNN, Decision Trees**), donde la **Regresión Logística** resultó superior.

### 📊 Resumen de Resultados (Summary of Results)

*   **Evolución de Éxito**: La tasa de éxito de SpaceX creció de un 0% inicial hasta alcanzar un **80-83%** a medida que aumentó la experiencia de vuelo.
*   **Rendimiento por Órbita**: Las órbitas de baja energía (**SSO/ES-L1**) mostraron un éxito total (100%), mientras que las de alta energía (**GTO**) representaron la mayor dificultad de recuperación.
*   **Sitios de Lanzamiento**: La plataforma **KSC LC 39A** destacó como la más confiable para cargas pesadas superiores a los 10,000 kg.
*   **Modelo Predictivo**: El algoritmo de **Regresión Logística** se consolidó como el más efectivo con una precisión (accuracy) de **0.83**, siendo clave para predecir aterrizajes exitosos.

