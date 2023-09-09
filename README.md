# midterm_project

## Title: 
Assessing Toronto’s Winter Services for People Experiencing Homelessness



### Summary:
We analyzed hypothermic risk factors and historical weather data in Toronto to assess the viability of a recent proposal – that Warming Centres for individuals experiencing homelessness should be opened at temperatures below -5°C, rather than the current threshold of -15°C.

Our findings suggest that an adjustment to the threshold is warranted. The current threshold provides relief on only 5% of days with increased hypothermic risk. 

The current threshold further fails to account for the highest hypothermic risk events. Total precipitation appears to be a more significant predictive factor for hypothermic risk than temperature, and precipitation occurs in greater quantities at higher temperatures. While hypothermic risk does increase as temperatures drop, the highest risk weather events typically occur at milder temperatures.

As a result, we do not recommend implementing the proposed threshold adjustment to -5°C. This change would require warming centres to open 10x as frequently while still failing to provide relief on the highest risk days.

The new threshold should combine a temperature threshold and a precipitation threshold. For example, setting a temperature threshold of 0°C alongside a precipitation threshold of 5mm would only modestly increase resource requirements (from roughly 5 to roughly 8 days per year) while providing coverage for the highest risk events.




### Inquiry Explanation:
Preparing for winter weather is a critical aspect of budget planning and resource allocation for many public and private organizations. 

As temperatures decrease, conditions become increasingly life-threatening for people experiencing homelessness (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6765826/). One study suggests the odds of hypothermia increase 1.64-fold for every 5°C drop in temperature and 1.1-fold for each millimetre of precipitation.

The City of Toronto’s current policy is to open warming centres when temperatures drop below -15°C. Recently, advocates have pushed for that threshold to be moved to -5°C.

We look at historical averages and recent trends in Toronto winter weather to visualize the impact of this change.



### Files:
'current_cleaned_canadian_climate_data.csv' contains daily Temperature, Precipitation, and Hypothermic Risk Factor data for 13 Canadian cities spanning from 1940-2019.

'midterm_EDA.ipynb' contains certain analyses and data transformations used in performing EDA.

'midterm_project_overview.docx' contains planning notes regarding the project.

'toronto_weather_analysis.twb' contains various visualizations related to Toronto's climate and the relative risk of hypothermia by date.



### Data:
Our data set included daily temperature and precipitation records for 13 cities across Canada, available at https://www.kaggle.com/datasets/aturner374/eighty-years-of-canadian-climate-data.

Figures regarding estimated hypothermia risk reference a study conducted on hypothermic events affecting unhoused people in Toronto – “Cold Weather Conditions and Risk of Hypothermia Among People Experiencing Homelessness: Implications for Prevention Strategies”, published in the International Journal of Environmental Research and Public Health https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6765826/.



### Presentation Points:
[Toronto Temperature by Date] is the distribution of Toronto’s weather
-	[Filter 1] is the number of days below -5°C
o	At a -5°C threshold, we expect warming centres to be open roughly 50 days per year, covering roughly 50% of days with increased Hypothermia Risk Factors.
-	[Filter 2] is the number of days below -15°C
o	At a -15°C threshold, we expect warming centres to be open roughly 5 days per year, covering roughly 5% of days with increased Hypothermia Risk Factors

We can see from this that a threshold of -15°C covers only the most extreme weather events and fails to cover most days with high hypothermic risk factors.

[Hypothermic Risk Factors] assesses the correlation between HRF and temperature, as well as HRF and precipitation. We can see that precipitation is the more effective predictor for high HRF weather events.



### Conclusions:
A threshold of -15°C for the opening of warming centres fails to effectively mitigate the risks faced by Toronto’s unhoused population. 

While decreasing temperatures do correlate with increasing risk of hypothermia, increasing temperatures correlate with higher levels of precipitation. This causes the highest concentration of hypothermic risk events to occur at milder winter temperatures.
