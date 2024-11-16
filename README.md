## Setting

This project assumed the role as a data analyst for a company called **Grin**

- **Grin**: A bike-sharing service located in **Berlin**, tailored for tourists and locals, currently considering optimization of its vehicle placement and expansion to Munich and Frankfurt.
- **Location**: Berlin is an ideal hub for this service due to its famous tourist attractions such as **Brandenburg Gate** and **Alexanderplatz**.
- **Unique Feature**: Grin offers users discounts at partner restaurants and tourist spots.

---

## Project Overview

two APIs were used:

- **Meteostat**: Weather data API.
- **Foursquare**: Place data API.

The collected data was cleaned and wrangled to make data-driven decision: finding optimal places across Berlin, Frankfurt and Munich with highest bike parks number and best general weather conditions to set up our vehicle stands nearby to maximize usage and return conveniency, and to tailor our marketing and promotional campaigns accordingly.

Entire year's bike park spots was simulated, and number of bikes nearest to each place and average weather conditions of each place were calculated, then visualizations were created to generate insights.

---

## Findings Summary

!(<visualizations/Plot 1 Bike Distribution By Place Category.png>)

The plot revealed the most popular bike park places by categories. Bikes can be placed outside of popular category of places in three cities and promotional campaigns can be designed accordingly. For example, users who rented bike at bike stands near restaurants could receive discount dining.

!(<visualizations/Plot 2 Average Wind Speed for Top 10 Places in Top 5 Categories.png>)
!(<visualizations/Plot 3 Average Precipitation for Top 10 Places in Top 5 Categories.png>)

After reveal of most popular categories of places, one can drill down to explore most popular places in those categories. At this granularity, weather conditions should be considered so average wind speed and precipitation level were not beyond safe threshold for biking. Since it's simulated data the result was nuanced and served only as a demonstration of analytic idea.