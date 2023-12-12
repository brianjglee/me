# Aspiring Data Scientist

#### Technical Skills: Python, SQL, Excel, PowerBI

## Projects
### Predicting Home Value with a Random Forest Regressor
[Project Link](https://github.com/brianjglee/zillow-time-series-rfr)

Scraped housing data from the Zillow website using **python**, imported into pandas DataFrame, cleaned, performed exploratory analysis, and created a machine learning model using random forest regressor to predict the home value of current listings.

### COVID Data Analytics
[Visualization Link](https://public.tableau.com/app/profile/jeong.gyu.lee/viz/CovidDashboard_17024232948120/Dashboard1?publish=yes)
![Image](/assets/covid-dashboard.png)

This project was my first forey into creating a database, and uploading, exploring, and visualizing data. I used Docker to create a container for mysql. Then using Azure Data Studio, I established a connection to the container. Using SQL queries, I created a database and two tables for my covid deaths and covid vaccinations. I used bulk upload to transfer data from csv files to these tables.

For my data exploration, I focused on looking at how infection rates, death rates, and vaccinations changed over time per location. I made use of aggregate functions, CTEs, and views to assist in doing so.

Finally, I extracted my tables into excel, connected to them in Tableau, and created a visualization of COVID deaths and infections over time. Thanks for taking a look!

### Personal Finance Dashboard using PowerBI
![Image](/assets/dashboard.png)

Extracted transactions from bank statement pdfs using **python**, imported into a csv file, cleaned the data in **PowerBI**, and created a personal finance dashboard that displays overall or monthly overview of spending and earnings. 

### Uber Supply and Demand Data Analysis
[Project Link](https://github.com/brianjglee/uber-supply-demand)

Using a provided dataset, we import the csv file into a **pandas** dataframe, clean the data, use **pandasql** for **SQL** style queries, and pandas **to_datetime**, **merge**, **plot**, and **groupby** functions to gather insights for the business. 

### Cocktail Recommendations using Natural Language Processing and 
[Project Link](https://github.com/brianjglee/cocktail-recommendations)
What cocktails do you like? How do you know what to order at a bar? Cocktails are overwhelming. The goal of this project was to use natural language processing to recommend cocktails. Using **spaCy's Named Entity Recognition (NER)**, we created a model to extract the names of cocktails that redditors enjoyed. With the help of **PRAW**, Reddit's webscraping API, we compiled a list of text from multiple reddit comments. Then, using the NER model, we extracted cocktail names from these posts. After creating a spell checker function, using the distance between two strings, we create a dictionary of cocktail names to correct the spelling mistakes in these posts. Finally, we explore the data using association rules. In particular, **mlxtend's frequent pattern growth algorithm** shows us commonly grouped cocktails in each post. We also created an **item item collaborative filtering** to recommend a cocktail using a correlation matrix. 

## Education
M.Ed., Mathematics Education | University of California, Santa Barbara (_June 2021_)

B.A., Mathematics | University of California, Santa Barbara (_June 2020_)

## Work Experience
**Math Teacher @ South High School, Torrance (_Auguest 2021 - June 2023_)**
- mapped algebra 1 and precalculus curriculum, designed and executed lesson plans, administered assessments and measured growth, and collaborated with teacher teams to analyze student success and improvement.
- piloted after school program to reach and support students with learning gaps from the pandemic by designing an assessment to identify struggling students, designed and implemented math intervention tactics. 
