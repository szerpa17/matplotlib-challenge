# Matplotlib Challenge

![Laboratory](Images/Laboratory.jpg)

This challenge entails the analysis and the generation of tables/figures needed for a technical report on an animal study conducted on 249 mice. The mice in the study were identified with SCC tumor growth that were treated through a variety of drug regimens, containing observed and measured tumor development over 45 days.

All analyses completed may be found within the [pymaceuticals.ipynb](https://github.com/szerpa17/matplotlib-challenge/blob/master/Pymaceuticals/pymaceuticals.ipynb) file.

## Tools

* Python
* Python Packages: 
    * Padas
    * Matplotlib
    * Scipy.stats
    * SEM
    * Numpy
    
## Observation Highlights

The gender among all mice used in each drug regimen study was near evenly split between male and female mice.

![Mice Gender Ratio](https://github.com/szerpa17/matplotlib-challenge/blob/master/Pymaceuticals/images/pandas_pie.png?raw=true)

Out of the four drugs ('Capomulin', 'Ramicane', 'Infubinol', 'Ceftamin') - Ramicane had the lowest tumor size median.

![Tumor volume by Tratment Box Plot](https://github.com/szerpa17/matplotlib-challenge/blob/master/Pymaceuticals/images/box_plot.png?raw=true)

There is a strong linear correlation between mouse weight and tumor volume (as the correlation result is over .70), therefore it is highly likely that the heavier the mouse, the larger their average tumor volume is.

![Mouse Weight vs Average Tumor Volume](https://github.com/szerpa17/matplotlib-challenge/blob/master/Pymaceuticals/images/regression_plot.png?raw=true)
