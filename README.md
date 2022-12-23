# WORLD_FACTORS
World Development Factors Project

Project "World Development Factors" is created with an idea to find the factors (features) that influence the global well-being of countries for the period of 1960-2020. 

Data.
1. Variables (features) data - World Development Indicators from World Bank Open Data. This is a dataset with 1442 development indicators for every country on Earth since 1960. Data is updated yearly. https://databank.worldbank.org/source/world-development-indicators/
2. Target data - Trading Economics Indicators (GDP, Inflation, Interest rate, Unemployment rate, Budget, Debt, Population). Snapshot for current date is available on their website https://tradingeconomics.com/matrix. Historical data is availavle for paid subscribtion.
3. Additional data - Natural Disasters Data 1900-2022 from https://ourworldindata.org/natural-disasters
4. Additional data - War and Peace Data 1946-2022 from https://ourworldindata.org/war-and-peace

Projects steps:
1. Load the data from the web and convert into DataFrames
2. Explore and visualize World Development Indicators 
3. Join Variables, Additional and Target datasets using Counry codes
4. Run ML experiment to identify the factors that drives the prosperity
5. Build a simulation model to run different scenarios.
