# Finish-Line-Forecasters-F1-Data-Driven-Foresights
This project dives into Formula 1 data using modern tools to predict race outcomes better than before. By blending various sources and machine learning, it aims to understand what affects drivers' performance and team standings. The goal is to make more accurate predictions and find new ways this tech could help in sports research

![giphy](https://github.com/b-kashyap/Finish-Line-Forecasters-F1-Data-Driven-Foresights/assets/155677382/fee7f643-89a8-40ad-9673-4651bf621685)

## Dataset Overview:
Utilizing the Ergast API and FastF1 Python Package, our research analyzes Formula 1 data from 1951 to 2023, detailing races, competition results, participant info, and performance metrics like lap times and pit stops. The dataset covers race specifics, circuit details, and historical evolution, reflecting track changes and safety standards. It also includes comprehensive information on constructors, team performance, driver careers, and performance metrics crucial for understanding race strategies and driver skills in Formula 1.

## Technologies and Libraries used:
Programming Language - Python <br>
pandas : For Data manipulation and analysis <br>
matplotlib : Plotting library for creating visualizations <br>
seaborn : Data visualization library based on matplotlib, for statistical graphics <br>
csv : Module providing classes for reading and writing CSV files<br>
scikit-learn : Python library, providing an array of machine learning algorithms and utilities for streamlined model development, assessment, and implementation <br>

## Feature Engineering and Exploratory Data Analysis:
The report underwent rigorous data preparation steps, including removal of missing values, non-finish instances, outliers, and redundant data, ensuring a clean and reliable dataset. Analysis focused on the 2016-2023 timeframe, merging datasets for comprehensive driver insights while employing exploratory data analysis (EDA) tools like bar charts and correlation matrices. Visualizations highlighted dominant racing teams, key tracks, and experienced drivers, with the correlation matrix revealing valuable variable relationships. While correlation aids understanding, caution was emphasized regarding inferring causation. Overall, EDA provided rich insights for stakeholders in Formula 1, aiding strategies, predictions, and a deeper appreciation of the sport's nuances.

## Model Development and Evaluation:
Seven models were built, including XG Boost, Random Forest, MLR, Ridge regression, Lasso regression, Linear regression, and Support Vector Regression. Notably, Random Forest Regression (RFR) emerged as robust in deciphering complexities within Formula 1 data using ensemble learning. Additionally, XGradient Boosting Regression (XGBR) demonstrated iterative refinement, showcasing adaptability for precision. Moving beyond numerical metrics, qualitative nuances highlighted the distinct impacts of each algorithm. Lap times and grid positions held significant sway, while Constructor ID surfaced as a nuanced factor, revealing the pivotal role of team strategies, influenced by constructors, in determining race outcomes.

## Future Scope:
1. Weather Conditions: Our goal is to refine predictive models by integrating real-time weather data, enabling adaptive strategies during races based on evolving weather conditions. <br>
2. Regulation Changes: We aim to proactively adapt our models to upcoming rule changes, providing insights into their potential impact on team performance and race outcomes.<br>
3. Technological Advancements: Exploring integration of the latest innovations in car design, simulation tools, and tire compounds to offer insights into how these advancements might reshape Formula 1 dynamics, ensuring our models stay at the forefront of analysis.<br>
