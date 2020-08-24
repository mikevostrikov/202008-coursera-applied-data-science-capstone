# Coursera Applied Data Science Capstone Project

In this project we explored Canadian National Collision Database dataset. We analyzed available attributes. We preprocessed data. We chose features and built a linear regression model for the car accidents severity. We were able to give practical and sensible data-based recommendations to drivers an traffic planners, thus successfully reaching the goals of this project.

_Discussion and interpretation_

Having the R^2 score of 0.1, model is not good at predictions of fatalities. However, the model is good enough for identification of important factors and their role in fatalities on the roads.

We can speculate that the fundamental factors behind all the identified influential independent variables are speed and visibility.

_Observations:_

* Night hours are the worst of all the factors. Low traffic leads to higher speeds. Lack of visibility makes driving even riskier.
* Traffic controls significantly decrease the traffic speed and thus fatalities.
* Weekend traffic is low and speedy. Risk of fatalities is higher.
* Presence of Sand/gravel/dirt on the road is not expected by the drivers and prooves to be dangerous.
* Roads curvature decreases visibility. Risk of fatalities is higher.
* Overcast weather as well as drifting snow, fog, smog, dust, smoke, mist decrease visibility. Risk of fatalities is higher.
* Raining and snowing (not including drifting snow) descrease visibility, but also significantly decrease the speed of the traffic. Drivers are extra careful. The risk of fatalities is lower.

_Recommendations to drivers:_

* Avoid driving at night
* Avoid driving in conditions with low visibility
* Respect traffic controls

_Recommendations to traffic planners:_

* Install traffic controls extensively
* Avoid sharp road curvatures when designing roads. Try to keep roads straight and level
* Controls are required to keep the roads clean. Presence of extraneous materials proves to be dangerous