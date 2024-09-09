# DataVis
Alex Patrone

INFO 250 -- 9/8/2024

Final Project

# Visualization Link

## Introduction
As the world attempts to reduce carbon emissions as the rapid effects of climate change take hold, it is important for us to understand our current reality in terms of past, present, and future. One of the largest sources of emissions comes from the oldest of humanity's industries: Agriculture. By analyzing and visualizing our modern CO2 emissions resulting from agriculture, we may be able to theorize on areas where emissions can most easily be reduced, as well as what actions are being taken now to reduce these emissions. Using the Agrifood CO2 emission dataset, and visualizing its findings on the Tableau [Agrifood Summary Dashboard], blahabaha

## Research Questions
1. How have global emissions changed overtime, in terms of amount, type, and location?
2. How does a country's population demographic alter its emissions?
3. Which countries are producing the greatest number of emissions, and what patterns do these countries follow?

## Dataset
For my project I plan to use the Agri-food CO2 Emission Dataset, as found on Kaggle and created by user Alessandro Lo Bello. This dataset compiles data from the Food and Agriculture Organization (FAO), and the Intergovernmental Panel on Climate Change (IPCC), both of which are organizations associated with and operated by the United Nations. The dataset is primarily describes the amount of CO2 emissions produced by different sectors in the agriculture and food industry. The data is historical, with records starting in 1990 and spanning until 2020. This dataset has roughly 7000 lines and 31 columns. Variables include, Area, Year, Emission Types, Population, Total Emission, and Average Temperature.

The Area variable contains a list of 236 unique countries and regions which the dataset records emissions for. It should be noted that some countries are split into subregions, namely China which is split between 5 distinct areas. Additionally, there is records for countries which from the start year and end year of the data had since dissolved, namely the USSR eventually dissolving into the Russian Federation and other successor states. Tableau allowed me to map non-extant countries and regions into modern day countries. The Year variable spans from 1990 to 2020. 

There are 23 emissions types which the dataset records, listed below:
![Emissions Table](https://github.com/user-attachments/assets/8df11e8f-54fa-4340-81f6-9fe7c176a9a1)

For easier analysis of the wide variety of emission sources, I categorized these 23 emissions into 7 groups, based on their descriptioned as provided by the dataset creator. It should be noted that the Net Forest Conversion variable did no corrrespond to CO2 emissions, but instead land area. For this reason, I did not include this variable when performing emissions analysis.

The Population variables are split between 4 separate values. These split the total population of a region between Rural and Urban populations, as well as Male and Female populations. It should be noted, that there is typically a difference between the sums of these populations, with the sum of Rural vs Urban typically skewing higher than the sum of Male vs Female. For this reason I chose to primarily use Rural vs Urban for population related analysis in order to maintain consistency.

The Total Emissions varible lists the total emissions from all sources of CO2 emission within the country. For better comparison, I prepared an additional variable, "Agrifood Emissions" which totals all Agri-food Emission types listed.

Finally, the Average Temperature variable notes the average temperature change in a region for the year. 

## Visualizations
### Global Emission Dashboard Visualization
[IMAGE]
This dashboard gives the user a broad look at the raw numbers and trends for the global theatre in terms of emissions. The dashboard allows the user to filter to find very specific data if need be. The top panel of the dashboard is the Geographics Emissions visualization, which aggregates all Agrifood emissions and applies a gradient colorscale to each countries' area, corresponding to the emissions produced (or in some cases reduced) by the country. The dashboard's first filter is for Year, which allows the user to play an animation of the emission gradient chaning overtime, or for a user to select a specific year. Next, the user may select to only look at selected emissions Categories, or all at once. The second panel is a Line Chart which shows the global change of emissions in each selected category. The dashboard's third filter allows a user to filter this line chart by individual countries, or multiple countries.

## Findings

## Conclusions

