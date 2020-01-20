# Data Science Portfolio
This repository contains several data science projects which I worked on or currently working on.

## Exploratory Analysis/Visualizations

### Project 1: Dashboard for Quality of Life Indicators
**language:** Python<br/>
**main libraries used:** plotly, dash<br/>
**context:** university group project<br/>
**contributors:** Nicolae-Radu Homorozan (M20190217@novaims.unl.pt), Alejandro Alvarez (M20190555@novaims.unl.pt), Bojan Stavrikj  (M20190562@novaims.unl.pt) <br/>

- In this project we created a dashboard for quality of life indicators of more than 140 cities, aiming to let users find their optimal city to live or make holiday in. 
- The dataset includes indicators for health care, safety, cost of living and air pollution. Additionally, we visualized weather data for the top cities.
- The project is deployed on heroku: http://paradise-finder.herokuapp.com 

### Project 2: Analysis of Investment Oppurtunities in the Tourism Sector
**language:** Python<br/>
**main libraries used:** pandas, bokeh<br/>
**context:** university group project<br/>
**contributors:** Nicolae-Radu Homorozan (M20190217@novaims.unl.pt), Francisco Guerreiro Galla Goucha Jorge (M20190863@novaims.unl.pt), Wenyi Liang (M20190551@novaims.unl.pt)<br/>

- In this project we analyzed tourism-related data for a set of worldwide countries, aiming to find the optimal choice for an investment in this sector. 
- From a set of 186 countries and data about international arrivals and toursim receipts we used the method described by the Modern Portfolio Theory (MPT) to identify the Efficient Frontier of the top 10 countries which yield the highest return for a given risk. 
- For these 10 countries we analyzed other external indicators such as investor protection, the cost of crime and terrorism, interest rates, GDP, access to loans, overall infrastructure and investment tax incentives, and created a ranking for each indicator. 
- Eventually, we calculated a weighted ranking of these indicators and visualized the result in a summary table


## Unsupervised Learning 
### Project 1: Customer Cluster Analysis for an Insurance Company 
**language:** Python<br/>
**main libraries used:** scikit-learn, scipy, sompy, plotly, pandas  <br/>
**context:** university group project<br/>
**contributors:** Lennart Dangers (m20190251@novaims.unl.pt), Pedro Santos (m20190420@novaims.unl.pt)
<br/>
**files:** *outlier_variations.py*: Comparing different outlier thresholds; *algorithm_selection.py*: Comparing different algorithms; *main.py*: Preprossing, feature engineering, applying final algorithm; *profiling.py*: Profiling of final clusters 
<br/>
- In this project we conducted a cluster analysis for a fictional insurance company, aiming to find a suitable customer segementation for personalized marketing campaigns. 
- The dataset consists of 10.000 customers with information about their salary, birth year, monetary value, claims rate and premiums per LOB.
- After preprocsseing the dataset we applied the following algorithms: Kmeans, Kmodes, Kprototype, Agglomerative Hierarchical Clustering, Self Organizing Maps, Mean Shift, DBScan and combinations of those. 
- Eventually, we obtained four clusters by using a Self Organizing Map followed by AHC.
