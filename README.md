# Applied Data Science - COVID 19 Data Analysis

The goals of this project,
* is to learn the best practices of data science from the industry while developing a COVID-19 analysis prototype.
* To trace the confirmed number, calculate the doubling rate and doubling time for 100+ countries.
* To generate SIR model simulation for 100+ countries.

The project focuses on the process of modeling (Python) and a methodology to approach a business problem.

The final result will be a dynamic dashboard - which can be updated by one click - of COVID-19 data with filtered and calculated data sets like the current Doubling Rate of confirmed cases

Techniques used are manual data gathering, Python Pandas, scikit-learn, Facebook Prophet, Plotly, Dash

For this, I have followed an industry-standard process (CRISP-DM) by focusing on the iterative nature of agile development

* Business understanding (what is our goal)
* Data Understanding (where do we get data and cleaning of data)
* Data Preparation (data transformation and visualization)
* Modeling (Statistics, Machine Learning, and SIR Simulations on COVID Data)
* Deployment (how to deliver results, dynamic dashboards in python)

The entire project follows the development flow of a rapid prototype project.

## First look of Dash Board

![First dynamic dashboard](/reports/figures/plotly_result.png)

## Final look of Dash Board
In final look, the dashboard is divided into 3 sections,

* Timelines confirmed, doubling rate
  Timelines confirmed:Number of confirmed cases registered for a particular country. 
  Doubling rate: Rate at which a country's confirmed cases are doubling. 
  Doubling rate filtered: Doubling rate data is filtered using 'Savgol filter' for better forecast.
  
![Timeline](/reports/figures/Timeline_dash.PNG)

* SIR model: S: Susceptible, I: Infected, R: Recovered
  An SIR model is an epidemiological model that computes the theoretical number of people infected with a contagious illness in a closed population over time.

![SIR model](/reports/figures/SIR_dash.PNG)

* World map: Shows the confirmed cases for each country.

![World Map](/reports/figures/World_map.PNG)

Final look of Dash Board

![Final dynamic dashboard](/reports/figures/Final.PNG)

