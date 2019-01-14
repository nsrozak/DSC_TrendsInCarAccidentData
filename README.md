Finding trends in data about car accidents to learn about the conditions car accidents occur.


# Introduction and Hypothesis

I used a Kaggle dataset about car accidents in the United Kingdom from 2005 to 2015. By observing trends in the data, I hoped to learn about conditions car accidents occur. Before exploring the data, I hypothesized that most accidents happen when dangerous circumstances arise like slippery roads or malfunctioning traffic signals.


# Methods

I used Python to complete this project. Here are the steps I followed:

(1) read the data into Python

(2) selecte specific columns to explore further

(3) clean data by removing missing values and duplicates

(4) create graphs to see trends in the data. I used histograms, pie charts, box charts, bar graphs, and scatterplots

(5) interpret graphs to find trends in the data

(6) formed a conclusion  


# Conclusion

Variables Unrelated to Driving Conditions

* most accidents happen during the hours where most people are awake, and they are scattered fairly evenly across the days of the week.

* most accidents materialize on single carriageway roads with speed limits between 30 and 40 miles per hour. Roads like this are often found in suburbs. 

Variables Related to Driving Conditions

* most accidents occur under safe and normal conditions.

Variables Related to the Accident

* most accidents are minor with a small number of vehicles involved. 

Variables Related to Pedestrians in the Accident

* when pedestrians are involved in a car accident, usually there are no safety features such as a crossing guard or traffic signal to alert drivers about the pedestrian’s presence. 

Comparing Variables to Number of Casualties

* number of casualties is an indicator of accident severity, so I chose to examine that.

  * there is a positive relationship between speed limit and average number of casualties. This relationship is roughly linear. 
  
  * there is a positive relationship between number of vehicles and average number of casualties. The relationship trends in an exponential direction, aside from several outlier data points.
  
