### Airline Safety Analysis
## Project Description
# Overview
This project aims to assess the safety of various commercial airplanes using data from the National Transportation Safety Board. The goal is to identify airplanes that present the highest and lowest safety risks.

# Business Problem
The business problem is to determine which airplanes have the lowest risk factors. Client concerns include the number of injuries or fatalities to their customers. We will investigate the numbers of injuries and fatalities, and whether any external factors (such as weather, engine type, etc.) influence these numbers. Addressing these questions is crucial, as our client's investment will not thrive if they face costly litigation due to operating an unsafe airline.

# Data Understanding
Our dataset, sourced from the National Transportation Safety Board, spans from 1962 to 2023 and covers civilian aviation accidents and incidents in the USA and some international waters. The data includes variables such as the make and model of the aircraft, the number of fatalities and non-fatal injuries, weather information, the number of engines, and whether the plane was amateur-built. These factors will be considered in our analysis to recommend planes with the lowest numbers of fatalities and injuries.

# Methods
Data was analyzed under various conditions (weather, amateur-built, engine type) in relation to the total fatal injury average.
Data was filtered and grouped by airplane make and model.
Functions were created to further filter the data, determining if an airplane’s average injuries were lower than the standard deviation and if the number of uninjured passengers was higher than the standard deviation.
The filtered dataframe was used to identify the safest possible planes.

# Results
Weather factors contribute to an increase in total fatal injuries, with June and October having the highest average fatal injuries.
![weather](./images/Total%20Fatality%20Means%20by%20Month%20and%20Weather.png)

Engine type correlates with the number of total fatal injuries. For 'Turbo Fan' engines, an increase in the number of engines correlates with an increase in average total fatal injuries.
![engine](./images/Fatalities%20by%20Number%20of%20Engines%20and%20Engine%20Type.png)

The Airbus A380 is identified as the safest plane, with the highest number of uninjured passengers and a low average number of total fatalities per accident.
![engine](./images/Top%205%20Safest%20Planes%20Uninjured%20Passenger%20Count.png)

# Conclusions
We recommend our client purchase the Airbus A380, identified as the safest plane.
Avoid planes with 'Turbo Fan' engines.
Pay particular attention to higher fatalities during bad weather, especially under Instrument Meteorological Conditions (IMC) in June and October.
# Next Steps
Future improvements could include researching the frequency of plane usage and contrasting it with the number of accidents.
Mapping accident locations and analyzing 'Report.Status' values to determine if human error is a factor in accidents.
For More Information
See the full analysis in the Jupyter Notebook or review the presentation.

For additional information, contact me via GitHub.
=======
In the future we could improve this project by researching the frequency that each plane is used and contrast that to the number of accidents it is involved with. Additionally, we could map where the most number of accidents occur and also dig into the values represented in 'Report.Status', to determine if human error is a factor in any accidents.


# For More Information
See the full analysis in the Jupyter Notebook or review this presentation.

For additional info, contact me via github. 


## Repository Structure

```
├── images
├── zippedData
├── Airline Safety Data.pdf
├── Airline_Safety_Data_Analysis.ipynb
└── README.md
```
>>>>>>> origin/main
