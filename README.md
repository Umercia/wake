## Synopsis

In this study we investigate the impact of wind turbine type (rotor size, generator size and hub height) on the wake efficiency. The overall idea is to build a simple model that could be able to predict(/correct) the wake effect of a specific configuration (turbine type) based on another "reference" configuration. It should be noted that it is a "macro" approach that does not go into the details of the wake model equations.
4 turbine characteristics have been identified to potentially have an impact on the wake effect:

* hub height
* wind speed
* rotor size
* generator size

To build this model, 5 sites of 17 WTGs have been selected across the Northern Europe countries. On each site,
multiple configurations have been computed using winPRO 3.1 with the standard wake model (N.O Jense, WDC = 0.075). 
To assess the impact of each parameters on wake efficiency, a reference configuration has been chosen (hub height + rotor + generator) and from this reference, each parameter has been tuned one by one (keeping the other constant).
Results can be found on this link: [results](https://umercia.shinyapps.io/Wake_study/)

Main files:  
* "Wake_study.Rmd": R script generating the results html page.
* "wake_input.csv": data used to build the model.
* "wake_benshmark.csv": data used to benshmark the model.

