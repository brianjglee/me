# Electrical Engineer (Plasmonics/Communications/Microwave/RF)

#### Technical Skills: Lumerical FDTD, MATLAB, Python

Welcome! My current research projects involve translating ideas from microwave/RF electronics to tiny electromagnetic devices. Specifically, when visible and near-infrared (NIR) light interacts with subwavelength structures, strong field confinement supports resonant modes. Between metals and dielectric surfaces, this coupling excites surface plasmon polaritons, which are surface-bound electromagnetic waves associated with collective electron oscillations that propagate along the interface and decay away from it. We attempt to exploit microwave structures, like cavities and waveguides, and techniques, like impedance matching, to understand and enhance electromagnetic properties at the nanoscale.

Meanwhile, since I'm learning the physics and engineering principles behind microwave electronics, I'm designing high-frequency circuits as a hobby. Join me in my journey in all things electromagnetics! 

I also enjoy learning about data analytics, machine learning, and telecommunications! 

## Projects
Below are some projects in machine learning and data analytics I've completed in the past. 
## Predicting Home Value with a Random Forest Regressor
[Project Link](https://github.com/brianjglee/zillow-time-series-rfr)

Scraped housing data from the Zillow website using **python**, imported into pandas DataFrame, cleaned, performed exploratory analysis, and created a machine learning model using random forest regressor to predict the home value of current listings.

## Uber Supply and Demand Data Analysis
[Project Link](https://github.com/brianjglee/uber-supply-demand)

Using a provided dataset, we import the csv file into a **pandas** dataframe, clean the data, use **pandasql** for **SQL** style queries, and pandas **to_datetime**, **merge**, **plot**, and **groupby** functions to gather insights for the business. 

## Cocktail Recommendations using Natural Language Processing and 
[Project Link](https://github.com/brianjglee/cocktail-recommendations)
What cocktails do you like? How do you know what to order at a bar? Cocktails are overwhelming. The goal of this project was to use natural language processing to recommend cocktails. Using **spaCy's Named Entity Recognition (NER)**, we created a model to extract the names of cocktails that redditors enjoyed. With the help of **PRAW**, Reddit's webscraping API, we compiled a list of text from multiple reddit comments. Then, using the NER model, we extracted cocktail names from these posts. After creating a spell checker function, using the distance between two strings, we create a dictionary of cocktail names to correct the spelling mistakes in these posts. Finally, we explore the data using association rules. In particular, **mlxtend's frequent pattern growth algorithm** shows us commonly grouped cocktails in each post. We also created an **item item collaborative filtering** to recommend a cocktail using a correlation matrix. 

## COVID Data Analytics
[Visualization Link](https://public.tableau.com/app/profile/jeong.gyu.lee/viz/CovidDashboard_17024232948120/Dashboard1?publish=yes)
![Image](/assets/covid-dashboard.png)

This project was my first forey into creating a database, and uploading, exploring, and visualizing data. I used Docker to create a container for mysql. Then using Azure Data Studio, I established a connection to the container. Using SQL queries, I created a database and two tables for my covid deaths and covid vaccinations. I used bulk upload to transfer data from csv files to these tables.

For my data exploration, I focused on looking at how infection rates, death rates, and vaccinations changed over time per location. I made use of aggregate functions, CTEs, and views to assist in doing so.

Finally, I extracted my tables into excel, connected to them in Tableau, and created a visualization of COVID deaths and infections over time. Thanks for taking a look!
