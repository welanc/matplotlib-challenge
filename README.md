# MatPlotLib Challenge

## Task

Dummy pharmaceutical dataset of anti-cancer pharmaceuitical treatments on laboratory mice is cleaned and transformed using Python Pandas and Jupyter Notebook, with visualisations produced using Matplotlib. Data was cleaned of duplicate time points before generating a sumary statistics table consisting of mean, median, variance, standard deviation and SEM of the tumor volume for each drug regimen.

Plots generated include: 
* bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that show the number of total mice for each treatment regimen throughout the course of the study
* pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study
* box and whisker plot, using Matplotlib, of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style. Calculations of quartiles, Inter Quartile Range (IQR) and outliers were performed in order to achieve this
* scatter plot of mouse weight versus average tumor volume for a randomly selected mouse from the Capomulin treatment regimen
* linear regression model on top of the previous scatter plot, by first calculating the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment

A brief written summary of three observations from the data is included at the top of the Jupyter Notebook. 

--- 

## Technologies

* Jupyter Notebook

Python Libraries:
* Pandas
* NumPy
* MatPlotLib
* SciPy.stats



