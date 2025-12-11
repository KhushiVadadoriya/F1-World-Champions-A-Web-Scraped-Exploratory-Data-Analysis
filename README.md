# F1-World-Champions-A-Web-Scraped-Exploratory-Data-Analysis

## 🏎️ F1 World Champions: A Web-Scraped Exploratory Data Analysis

This project analyzes Formula 1 World Drivers’ Champions from 1950 to the present.
The dataset is scraped directly from Wikipedia using Python (Requests + BeautifulSoup), transformed into a structured DataFrame, and explored through comprehensive visualizations.

The goal is to uncover dominance patterns among drivers, constructors, engines, and tyre manufacturers, and to understand the relationships between key racing performance metrics such as wins, poles, points %, and championship margins.

## Project Overview

This analysis answers key questions such as:

* Which drivers have won the most championships?

* Which constructor (chassis) has won the most championships?

* Which tyre manufacturers appear most frequently in championship-winning seasons?

* Which engine manufacturer has the highest number of championships?

* Are pole positions related to winning the championship? (Wins, Poles, Margin)

* How dominant were champions in different seasons?
(Wins, Poles, Margin)

Through statistical exploration and visualization, we identify patterns of long-term dominance, competitive eras, and performance correlations.

## Data Collection

Data was scraped from the official Wikipedia page:
“List of Formula One World Drivers’ Champions”

Tools used:

* requests – Fetch webpage HTML

* BeautifulSoup – Parse the championship table

* pandas – Data cleaning + tabular structure

* matplotlib / seaborn – Visualization

The final dataset contains:

* 77 rows (champions)

* 16+ features
(Season, Driver, Age, Chassis, Engine, Tyres, Wins, Poles, Points %, Margin, etc.)

## Exploratory Data Analysis (EDA)
1️⃣ Drivers by Championship Wins

A bar plot highlighting the greatest champions:

* Michael Schumacher (7)

* Lewis Hamilton (7)

* Juan Manuel Fangio (5)

* Prost, Vettel, Verstappen (4 each)

Shows how rare sustained dominance is in F1.

2️⃣ Constructor Dominance

* Ferrari leads with 15 championships, followed by McLaren (13), Mercedes (8), and Red Bull (8).
The distribution shows a sharp dominance by a few top teams.

3️⃣ Tyre Manufacturer Dominance

* Goodyear (24) and Pirelli (20) have by far the highest counts, illustrating how tyre suppliers often define eras of performance.

4️⃣ Engine Manufacturer Dominance

* Ferrari (14), Mercedes (13), Ford (12), and Renault (11) emerge as the most successful engines powering champions.

5️⃣ Correlation: Poles vs Wins

<img width="513" height="436" alt="image" src="https://github.com/user-attachments/assets/b2e9671e-201d-4719-a0fc-9bfb4cd046a2" />
<img width="646" height="477" alt="image" src="https://github.com/user-attachments/assets/c6a804ad-46c6-4864-8346-bf574fd88021" />


A scatter plot and correlation heatmap reveal:

* A moderate positive correlation between poles and wins (≈0.66)

* Wins correlate more strongly with margin than poles

Not all champions rely on qualifying performance — many win from race craft

## Technologies Used

* Python

* BeautifulSoup4

* Requests

* Pandas

* Matplotlib

* Seaborn

* Regex

## Key Takeaways

* F1 dominance is heavily concentrated among a few drivers and teams.

* Pole positions help but do not guarantee championship wins.

* Engines and tyre suppliers play a critical role in long-term success.

* Championship margins reveal which seasons were competitive vs one-sided.

* Web-scraped data can be transformed into meaningful insights with simple tools.

## Future Improvements

* Add constructor/engine timelines across seasons

* Build an interactive dashboard (Power BI, Tableau, Plotly)

* Extend dataset to include race-level statistics

* Predict dominance metrics using machine learning models

## Acknowledgements

* Data sourced from Wikipedia (public domain).
* Formula 1™ is a trademark of Formula One Licensing B.V.

## Contact 

Khushi Vadadoriya

📧 Email: vadadoriyakhushi18@gmail.com

🔗 LinkedIn: www.linkedin.com/in/khushi-vadadoriya-0977ba249
