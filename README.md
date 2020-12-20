# The-Relationship-Between-COVID-19-Infection-Rates-and-Social-and-Economic-Factors
This project analyzes global COVID-19 infection rates. Moreover, the project attempts to build a regression model that predicts infection rates based on certain social and economic factors.

# Project Description
In this project, I attempt to do several things. First, I examine global infection rates of COVID-19. Second, I examine the infection rates in the United States, and compare the U.S. rates with other countries. Finally, I develop a regression model that predicts a country's maximum infection rate of COVID-19.

# Research Problems
1. What do the COVID-19 infection numbers look like across the globe?
2. What is the infection rate for the United States?
3. How does the U.S. infection rate compare to the infection rates of similar countries in different parts of the world?
4. Are there positive correlations between a country's infection rate and certain social and economic factors?
5. Can we build a regression model that predicts a country's infection rate based on a specific collection or subset of social and economic factors?

# Methodology and Strategy
1. Import necessary libraries and modules
2. Import the data
3. Perform initial feature selection
4. Perform exploratory data anlalysis
5. Calculate the maximum infection rates for countries
6. Clean, process, and merge the data
7. Analyze correlation and construct simple linear regression models using Pearson correlation coefficients and P-values
8. Build a multiple linear regression model and evaluate them using R-squared
9. Discuss and summarize the results

# Results
1. The United States had the highest rate of COVID-19 infections from January 2020 to December 2020.
2. The top 10 countries with the highest number of total infections were the following (in order from highest to lowest): United States (17206647), India (9979447), Brazil (7110434), Russia (2736727), France (2483524), Turkey (1955680), United Kingdom (1954268), Italy (1906377), Spain (1785421), and Argentina (1524372).
3. The top 10 countries with the least amount of total infections were the following: Vanuatu (1), Samoa (2), Marshall Islands (4), MS Zaandam (9), Solomon Islands (17), Holy See (27), Saint Kitts and Nevis (28), Timor-Leste (31), Laos (41), and Fiji (46).
4. The United States also had the highest masimum infection rate within a single day. This was calculated to be 247403 new COVID-19 cases in a single 24 hour period.
5. There is a positive correlation between a country's maximum infection rate and the variables GDP per capita, Life Expectancy, and Social Support. Both GDP per capita and Life Expectancy provided the most correlation with the target.
6. We can construct a mulitple regression model using both GDP per capita and Life Expectancy as predictors. But the R-squared score achieved is only 0.1120898004917733.

# Dependencies 
This project uses Python 3, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, and Scipy.

# Acknowledgements
Special thanks to Johns Hopkins University for compiling the COVID-19 data. The particular dataset for confirmed COVID-19 cases was provided by The Humanitarian Data Exchange. The dataset can be downloaded here: https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases?force_layout=desktop#
I want to also thank the Sustainable Development Solutions Network for providing the 2020 World Happiness Report. The data can be retrieved at this site: https://worldhappiness.report/ed/2020/
Finally, I want to thank Ahmad Varasteh for providing several bits of code that helped me develop this project. The code he wrote for the for loop to get maximum infection rates for each country was incredibly useful.
