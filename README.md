# Space Race: Determining SpaceX Rocket Landing Success with ML
#### by Sami Khalayli

## Overview
This capstone project explores the factors influencing the success of SpaceX rocket launches and landing through machine learning (ML). Utilizing data sourced from SpaceX's API and web scraping techniques, the project combines predictive analytics and visual data exploration to provide insights into the space industry's challenges and advancements. It is the final project of the 10-course "IBM Data Science Specialization".

## Executive Summary
My investigation dives into multiple aspects of rocket launches, including site efficiency, payload mass, and orbit types. By leveraging classification models such as K-Nearest Neighbors (KNN), Logistic Regression, and Support Vector Machines (SVM), this project attempts to uncover patterns that might predict launch outcomes and first stage landing successfully.

## Methodology
- **Data Collection**: Data was extracted using SpaceX’s API and web scraping Wikipedia using BeautifulSoup.
- **Data Wrangling**: Utilized Pandas for data cleaning and preprocessing.
- **Exploratory Data Analysis (EDA)**: Performed using both visual techniques and SQL queries.
- **Interactive Visualizations**: Developed using Folium for mapping and Plotly Dash for dynamic web dashboards.
- **Predictive Modeling**: Classification models were built and evaluated, focusing on understanding the model's ability to predict successful launches.

## Results
- **EDA Findings**: Different launch sites show varying success rates, with some achieving up to 77%.
- **Predictive Analysis**: Demonstrated that while logistic regression, KNN, and SVM models performed well, decision trees overfitted and underperformed on unseen data.
- **No direct correlation** was found between payload mass and launch success.

## Key Visualizations
1. **Launch Success Trends**: Line charts showing the yearly improvement in launch success rates.
2. **Site Efficiency Analysis**: Pie charts and scatter plots in the Plotly Dash application depicting success rates by site and the relationship between payload mass and launch success.

## Conclusions
- **Strategic Location Benefits**: Launch sites near coasts leverage Earth's rotation and enhance safety by reducing overland debris risks.
- **Model Effectiveness**: The use of robust models like SVM and logistic regression helps in accurately predicting launch successes, highlighting the importance of selecting appropriate algorithms to avoid overfitting.
- **Operational Insights**: High success rates in specific orbits indicate operational and technical strategies that can be replicated or improved for future launches.

## Future Work
- Extend the analysis to more recent launches and additional variables.
- Explore deeper ensemble methods to improve model performance.
- Integrate real-time data updates for dynamic prediction capabilities.

This project not only sheds light on the complexities of rocket launches but also offers tools and insights that can assist newer companies in the space sector to enhance their predictive capabilities and strategic planning.
