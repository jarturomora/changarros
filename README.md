# Quiero mi Changarro / I want my Shop

## Motivation
Have you ever wanted to be your own boss? how many times did you tried to start your own business but you failed? One of the main obstacles when someone wants to start his own business is the fear to invest all his money and lose it if the business fail. Could it be possible to predict what kind of business would succeed in certain city or neighborhood? I believe it is if you play with the accurate data; increasing the probability of success for a new small business is the goal of my project.

I live in Mexico, a beautiful country that is full of “Changarros”, they are a kind of little shops of business that are normally runned by a family as a way to have extra money for living expenses. According to the National Institute of Statistics and Geography of Mexico (INEGI: acronym from the Spanish name of this institution “Instituto Nacional de Estadística y Geografía”), there are around six million of “Changarros” or small business in Mexico, however every year around 75% of these new small companies disappear. One of the main reasons is the the line of business wasn’t attractive to the potential customers on the city or neighborhood where the “Changarro” was opened or that there were too many competitors.

This project will be aimed to help people who want to open a “Changarro” in Mexico to select the best line of business for a specific city or neighborhood according to have a successful business. To achieve this goal I will use data from the Mexican Economic Census to identify the most successful commercial activities per region, as well as the Population Census to verify if the population growth impacts the probability of success of a commercial activity or line of business.

For the purpose of this project, a “Changarro” will be a micro business that employs up to ten people. According to INEGI, “Changarros” represent 95.4% of the establishments across the country, despite “Changarros” only contribute with the 9.8% of the Mexican gross product, they employ the 39.8% of the Mexican workforce, that’s why I believe it is important to ensure their success since people working in this micro business are the main economic support for thousands of families in Mexico.

## Data Sources
All the data that will be used in this project during its preliminary phase of exploratory analysis will be gathered from the official website of INEGI (http://www.inegi.org.mx). Unfortunately INEGI doesn’t have a webservice or API to access all its data, so all the datafiles will be manually downloaded from the web page with the results of the national survey of micro-businesses: http://www.inegi.org.mx/est/contenidos/proyectos/encuestas/hogares/modulos/enamin/default.aspx.


These data files aren’t big in terms of MB, they contain a sample of almost 30,000 micro-business in Mexico that are representative of all the economic activities in the country. The source files are in DBF format, so a data preprocessing will be done to convert the DBF files into CSV files to ease their treatment during the analysis.
