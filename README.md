# Portfolio Project

## World Happiness Report 2005 - 2021

The World Happiness Report is an annual report released by the UN using data collected from the Gallup World Poll. The report is a survey of the overall state of global happiness. Respondents are asked to imagine a ladder on a scale of 1 (worst life imaginable) to 10 (best possible life). This concept is known as a Cantril Ladder.

The current columns (variables) preceding Happiness Score estimate the extent these factors contribute to life evaluations:

* `Log GDP per capita`
* `Social support`: having someone to count on in times of trouble (friends or family)
* `Healthy life expectancy at birth`: life expectancies at birth are based on the data extracted from the World Health Organization
* `Freedom to make life choices`: “Are you satisfied or dissatisfied with your freedom to choose what you do with your life?”
* `Perceptions of corruption`: national average of the survey responses to two questions in the GWP: Are there perceptions of widespread corruption in business and government
* `Generosity`: “Have you donated money to a charity in the past month?”
* `Positive affect`: The average of three positive affect measures of happiness, laughter and enjoyment experienced daily (binary response)
* `Negative affect`: The average of three negative affect measures of worry, sadness and anger experienced daily (binary response)

These factors do not directly contribute to the Happiness Score, however they can help to explain differences between countries and why some rank higher than others. The variables were determined mainly from the averages of (0: No) or (1: Yes) responses from respondents that participated in the survey.

Further information may be found here on the World Happiness Report website:
*https://happiness-report.s3.amazonaws.com/2021/Appendix1WHR2021C2.pdf*

Throughout the analysis `Ladder Score` will refer to Happiness score (it is the national average response to the question of life evaluations; subjective well-being)
* What are the trends of World Happiness from 2005 to 2021?
* What factors contribute most to world happiness?
* Which Regions are the "most happy" (Highest Score) ?
* What countries have the highest and lowest happiness scores?
* Which countries have a happiness score equal to or higher than United States?

The world happiness report website includes extra data related to COVID-19 mortality for year 2020. https://worldhappiness.report/ed/2021/

* `Gini coefficient of income`: measure of the distribution of income across a population; a higher percentage indicates greater income inequality
* `COVID-19 deaths per 100,000 population in 2020`: recorded COVID-19 deaths per 100,000 people 


This country Population dataset found on kaggle.com includes statistics concerning population change, population density, median age and other variables that may be used to show any possible correlations between happiness score and population stats. https://www.kaggle.com/tanuprabhu/population-by-country-2020

* `Yearly Change`: Yearly population change
* `Net Change`: Net change of country population
* `Density (P/Km²)`: Population Density
* `Land Area (Km²)`: Land area in kilometers sqaured
* `Migrants (net)`: Net change of migrants
* `Fert. Rate`: Growth rate/ fertility of a country
* `Med. Age`: Median age 
*  `Urban Pop %`: Percentage of population living in urban areas



We'll be utilizing the Python programming language and the Pandas library to perform the analysis. Matplotlib and Seaborn will be our primary libraries for visualizing our data.
