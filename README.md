# Development of a Forecasting Model for Tropical Solar Energy Systems Using Support Vector Machines
This repository contains a tropical solar energy forecasting model using support vector machines, developed as part of an accepted research paper at the International Conference on Applied Energy 2019 (ICAE 2019).

## Abstract
Solar energy is a sustainable source that is favored in tropical areas where the resource intensity is high. However, developing accurate forecasting models, which is crucial in the optimal design and operation of tropical solar energy systems, has been challenging due to the high-dimensional nature of the system. This study presents a novel forecasting model for such systems using support vector machines. The proposed model was developed using a data-driven methodology. Model optimization and feature selection were applied to improve predicting accuracy. Modeling results show that the medium Gaussian function provided the most desirable balance between the accuracy and speed of the training functions. The previous hour observation was found to be the most significant input, while some variables considered in the initial model caused overfitting. The final model had superior accuracy over the initial models and those developed in the literature, thereby validating the effectiveness of the presented methodology.

## About the Dataset
The National Solar Radiation Data Base (NSRDB) is an open dataset of solar radiation and weather data across various locations in the United States. Weather data were acquired from meteorological stations while the solar radiation data were modeled using National Renewable Energy Laboratory's (NREL's) Physical Solar Model (PSM). The dataset was accessed through its application programming interface (API). Documentation on the dataset can be found [here](https://doi.org/10.1016/j.rser.2018.03.003), while the dataset can be accessed [here](https://nsrdb.nrel.gov).

## About the Model Script
The model script was written in MATLAB R2019a using [MATLAB Live Editor](https://www.mathworks.com/products/matlab/live-editor.html), an interactive script editor that enables the model code to be integrated with formatted text and graphics.

## Directory
* [__/ModelResults/__](/ModelResults/) - contains the .mat files of the results from executing the model
* [__/RawData/__](/RawData/) - contains the .csv files of the downloaded raw data from NREL's NSRDB database
* [__/SolarEnergyForecastingModel__](/SolarEnergyForecastingModel.mlx) - contains the .mlx file of the model script written in MATLAB R2019a's Live Editor

## Contact Details
Aaron Jules R. Del Rosario, Graduate Student, Mechanical Engineering Department, De La Salle University (DLSU), Manila, Philippines | [E-mail](aaron_jules_delrosario@dlsu.edu.ph) | [DLSU Mechanical Engineering Department](https://www.dlsu.edu.ph/colleges/gcoe/academic-departments/mechanical-engineering/)
