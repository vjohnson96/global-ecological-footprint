# Data Analysis - Global Ecological Footprint

## Project Overview
This project consists on analysing data of the Global Ecological Footprint with Python, aiming to reach insights over this relevant theme and answer some important questions: 
- Which are the countries with the bigger ecological footprint?
- How does each global region contribute individualy?
- Is it possible to relate the countries ecologial footprint with other aspects?
To perform this analysis the following Python libraries where used: Pandas, NumPy, Matplotlib and Seaborn.
The dataset used gathered data up to 2023 and contains 24 columns, from which 4 were extracted to develop the study.
source: https://www.kaggle.com/datasets/jainaru/global-ecological-footprint-2023

## Why analyse the Ecological Footprint?
As the year go by, any theme regarding Earth's health gains more importance. I personally enjoy spending time in Nature, so its conservation is a theme that has my attention.
The Ecological Footprint is sustainability indicator used to understand the impact of natural resources consumption by society. In other words, it corresponds to the number of productive areas, measured in global hectares (gha), necessary to genreate all products and services for our every day necessities (source: WWF). 
In terms of numbers, as the global footprint increases, higher is the impact on the environment.

## Data Analysis and Results
To check the Data Analysis step by step, Click [HERE](https://github.com/vjohnson96/global-ecological-footprint/blob/main/project_global_footprint.ipynb)

At the end of the analysis it was possible to reach the following conclusions:

Bellow are the top 10 countries with the higher ecological footprints in the world.
It was surprising to see that 4 out of ten countries are from Middle East/ Central Asia region.

![Image](https://github.com/vjohnson96/global-ecological-footprint/blob/main/Visualizations/Top10countries.PNG)


Bulding up from the insight given by the first visualization, reveal how each region contributes becomes an interesting idea.
To do so, the data was grouped by region, calculation the mean and total ecological footprint consumption
It's possible to visualize the result on the bar plot bellow:


![Image](https://github.com/vjohnson96/global-ecological-footprint/blob/main/Visualizations/GlobalRegion.PNG)

Through the years of study of ecological footprint, specialist got to the conclusion that the more developed and strongly industrialized countries have a higher Ecological Footprint. To confirm this affirmation a scatter plot was built to visulize the correlation between the 'Per Capita GDP' and 'Total Ecological Footprint':

![Image](https://github.com/vjohnson96/global-ecological-footprint/blob/main/Visualizations/Scatter.PNG)

The 2 variables present a correlation of 0.80, suggesting a strong relationship between them!

## Learnings and Next Steps
The project was fully developed in Jupyter Notebook IDE, and that was the idea from the start. Provide quick answers and visualizations in the IDE to easily understand the problem was the goal, and at the end it was achieved.
Mission acomplished, but what's next? Despite the good quality of the visualizations developed with seaborn and matplotlib, the aim is to make it even better with a PowerBI dashboard. 
