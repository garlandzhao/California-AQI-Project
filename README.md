# California-AQI-Project
The purpose of this project is to analyze and visualize the air quality of California. Air quality is measure as AQI or air quality index. The lower the AQI value, the better the air quality. A high AQI value indicates a high amount of pollutants in the air. This project uses public data from the Environmental Protection Agency(EPA).

## Tools/Technology
- Excel
- Python
- Tableau

#### Main Libraries Used
- Pandas
- Darts
- Matplotlib

After obtaining the air quality index data from the EPA website, the data was imported into Excel. Excel is used to clean, edit, and merge the gathered data into a singular dataset file. The file was then analyzed with Python. Python was used to train a neural network model to forecast future air quality index values. The results of the project was visualized with Tableau.

## Tableau
![California AQI Animation](https://github.com/garlandzhao/California-AQI-Project/blob/8412032eaee8b9f0ebd84e4796bc12a1c6c59a3d/California%20AQI%20Project/Media/Map%20Animation.gif)



[Tableau Map Link](https://public.tableau.com/app/profile/garland.zhao/viz/CaliforniaAQI/Map?publish=yes)

The animation above displays the change of air quality over time in each of the California counties. The animation shows data from 1981 to 2022.

![California AQI Line chart](https://github.com/garlandzhao/California-AQI-Project/blob/8412032eaee8b9f0ebd84e4796bc12a1c6c59a3d/California%20AQI%20Project/Media/Line%20chart.png)



[Tableau Line Chart Link](https://public.tableau.com/views/CaliforniaAQI/Linechart?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

The line chart above displays the AQI value for the LA county, Orange county, and San Diego county from 1981 to 2022.


## Forecasting

![California AQI Forecast chart](https://github.com/garlandzhao/California-AQI-Project/blob/8412032eaee8b9f0ebd84e4796bc12a1c6c59a3d/California%20AQI%20Project/Media/Forecast%20Line%20chart.png)



[Tableau Forecast Chart Link](https://public.tableau.com/views/CaliforniaAQI/ForecastLinechart?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

The image above displays the forecasting of the LA county for the next 5 years. The future median AQI values are forecasted to be lower over time.


## Notes
- The datasets use a "|" delimiter
- EPA Data: https://www.epa.gov/outdoor-air-quality-data/air-quality-index-report
