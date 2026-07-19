# Global Diet and Health Analysis

## What this project is about

##### I wanted to explore a simple question: does what a country eats say anything about how healthy its people are? This project looks at dietary habits, like egg, milk, meat, sugar, fruit and vegetable consumption, across countries and compares them against health outcomes like life expectancy, obesity and diabetes prevalence.

##### The workflow of this project goes like: cleaning raw data from multiple public sources, merging it into a single country-level dataset, exploring it with Python and finally building an interactive Tableau dashboard so anyone can dig into the patterns themselves instead of just reading a static report.

## Data sources

##### Everything is pulled from public datasets and merged on a country-code basis:

* ##### FAOSTAT – food consumption by category (kg/capita/year)
* ##### World Bank Open Data – GDP per capita (US$)
* ##### Our World in Data – life expectancy (years), obesity rates (%), and diabetes prevalence (%)

## Tools used

* ##### Python (Pandas, NumPy) and Jupyter Notebook for cleaning, merging and exploratory analysis of the data
* ##### Tableau Public for creating the interactive dashboard

## What I found

##### A few things stood out once the data was cleaned and correlated:

* ##### Egg and milk consumption both correlate fairly strongly with life expectancy (r = 0.67 and 0.64). Countries that eat more eggs and dairy tend to live longer on average.
* ##### Meat consumption correlates with both life expectancy (r = 0.58) and obesity (r = 0.62), so it cuts both ways.
* ##### Sugar has a moderate relationship with obesity (r = 0.44) but almost none with diabetes prevalence (r = 0.08), which was surprising because sugar and diabetes are so often linked together.
* ##### Obesity and diabetes are moderately correlated (r ≈ 0.58), which makes sense but it's a reminder that diabetes is driven by more than diet alone.
* ##### GDP per capita has the strongest relationship with life expectancy (r = 0.68). This raises an interesting question the dashboard is built to explore further: how much of the "healthy diet" effect is actually just a wealth effect in disguise? 

## The dashboard

##### Rather than just repeating the static charts from the notebook, I built a Tableau dashboard to let you explore the data yourself.

!\[Dashboard](tableau/Dashboard.png)

## Explore it live here

##### https://public.tableau.com/app/profile/chinmoyee.bhuyan4922/viz/GlobalDietandHealthAnalysis/GlobalDietandHealthAnalysisDashboard

## How the project is organized

##### global-diet-health-analysis/

##### &#x20; data/

##### &#x20;   raw/

##### &#x20;   processed/

##### &#x20;

##### &#x20; notebooks/

##### &#x20;   001-data-cleaning.ipynb

##### &#x20;   002-data-merging.ipynb

##### &#x20;   003-exploratory-data-analysis.ipynb

##### &#x20; tableau/

##### &#x20;   Global\_Diet\_and\_Health\_Analysis.twbx

##### &#x20;   Dashboard.png

##### &#x20;   Interactive Diet Map.png

##### &#x20;   Interactive Health Map.png

##### &#x20;   Interactive Scatter Plot.png

##### &#x20;   Correlation KPI.png

##### &#x20; README.md

##### &#x20; requirements.txt

## Why I built this 

##### This is my first big project built from scratch and I wanted it to be something I actually cared about. I'm a huge foodie, so I knew I wanted to do something related to food. After thinking for a while, the idea clicked: what if I looked at how dietary patterns differ from country to country and whether that connects to how healthy people actually are? Once I had that question, everything from the data collection, the cleaning, the analysis, followed by to get a proper answer.


## About me

##### Chinmoyee Bhuyan

* ##### GitHub: https://github.com/chinmoyeedata
* ##### LinkedIn: https://www.linkedin.com/in/chinmoyee-bhuyan/

###### Note: Notebooks use local file paths and were built on Windows. 

###### To re-run them in your device, update the paths in each notebook.

