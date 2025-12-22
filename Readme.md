Summary of methodologies

Data Collection: Technical data was extracted using the SpaceX API and supplemented with historical information obtained via web scraping from Wikipedia.

Data Wrangling: The data was transformed from JSON to DataFrames, filtering exclusively Falcon 9 missions and removing null values to ensure the quality of the dataset.

EDA (Visual & SQL): SQL queries and statistical graphs were used to identify key trends, such as the relationship between flight number and improvement in success rate.

Interactive and Predictive Analysis: A geospatial analysis was performed with Folium and dashboards in Plotly Dash to segment success by load and location, while in the predictive stage, after evaluating models such as SVM and KNN, Logistic Regression proved to be the superior algorithm with an accuracy of 0.83.
Summary of all results
SpaceX's success rate grew from 0.0 to 80% as flight experience increased. Low-energy orbits (SSO/ES-L1) were identified as completely successful, while high-energy orbits (GTO) presented the greatest difficulty in recovery. The KSC LC 39A site stood out as the most reliable for heavy loads exceeding 10,000 kg. Finally, after evaluating several algorithms, Logistic Regression proved to be the best predictive model with 83% accuracy, being particularly effective in identifying successful landings.
