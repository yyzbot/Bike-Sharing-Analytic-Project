![](Grin_Logo.png)
## Setting

This project assumed the role as a data analyst for a company called **Grin**

- **Grin**: A bike-sharing service located in **Berlin**, tailored for tourists and locals, currently considering optimization of its vehicle placement and expansion to Munich and Frankfurt.
- **Location**: Berlin is an ideal hub for this service due to its famous tourist attractions such as **Brandenburg Gate** and **Alexanderplatz**.
- **Unique Feature**: Grin offers users discounts at partner restaurants and tourist spots.

---

## Project Overview

two APIs were used to extract weather and place data:

- **Meteostat**: Weather data
- **Foursquare**: Place data

Aim was to find optimal places with highest bike popularity and best weather conditions to set up vehicle stands nearby, and to tailor marketing campaigns accordingly.
Combined API data with simulated bike traffic data and wrangled to calculate number of bikes nearest to each place and average weather conditions of each place.
Visualizations were made based on the combined data to generate insights.

---

## Findings Summary

![](<visualizations/Plot 1 Bike Distribution By Place Category.png>)

The plot revealed the most popular bike park places by categories. Bikes can be placed outside of popular category of places in three cities and promotional campaigns can be designed accordingly. For example, users who rented bike at bike stands near restaurants could receive discount dining.

![](<visualizations/Plot 2 Average Wind Speed for Top 10 Places in Top 5 Categories.png>)
![](<visualizations/Plot 3 Average Precipitation for Top 10 Places in Top 5 Categories.png>)

After reveal of most popular categories of places, one can drill down to explore most popular places in those categories. At this granularity, weather conditions should be considered so average wind speed and precipitation level were not beyond safe threshold for biking. Since it's simulated data the result was nuanced and served only as a demonstration of analytic idea.