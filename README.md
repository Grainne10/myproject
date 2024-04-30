# My Project

**by Grainne Boyle**
I am a student at the [Atlantic Technological University] (https://www.atu.ie/), Galway, studying the Higher Diploma in Science in Data Analytics on a part-time basis over 2 years.  This repository contains the files for  my submission of the project for the principles of data analytics module.

I work at [TE Connectivity] (https://www.te.com/usa-en/home.html). I am new to programming and coding .

**Contents:** 

1. [Overview](#Overview)
2. [Description](#Description)
3. [Research](#Research)
4. [Comparisons](#Comparisons)
5. [References](#References)



# Overview

There are the main files for this project:

* Penguins.ipynb - This file will show an analysis of the Palmer Penguin Dataset using Python code. 
* Readme.md -  The Readme file accompanies the Jupyter notebook file . You should read this document first. It is a text file that contains information for the user about the project, code and research. It contain links and references.
* GitIgnore - The gitignore file specifies intentionally untracked files that Git should ignore. I have edited it and committed by hand when I had files that I wished to ignore. 
* Requirements - This shows the programs and libraries I have used to run the code and visualisations.
* All graphs and plots are shown in individual png format in the same folder.

# Description

![Palmer Penguins Image](https://allisonhorst.github.io/palmerpenguins/logo.png)

This project is based on the palmer penguins dataset.  The dataset is available [on GitHub](https://allisonhorst.github.io/palmerpenguins/) .  

The data for the Palmer Penguin project were collected by Dr. Kristen Gorman from 2007 to 2009. It was done by [Palmer Station Long Term Ecological Research Program](https://pallter.marine.rutgers.edu/), part of the US Long Term Ecological Research Network. This network provides a long term view of the events that reshape ecosystems by making long observations publicly available, develop and maintain large scale experiments and train graduates in interdisciplinary collaborative team science.  

The palmerpenguins data contains size measurements for each of the three penguin species: Adelie, Gentoo, and Chinstrap. They were observed on three islands in the Palmer Archipelago, Antarctica. It looks at size measurements and sex for 344 adult penguins.  

A brief description on the three penguin species and others can be found at [Oceanwide Expeditions Blog](https://oceanwide-expeditions.com/blog/meet-all-6-antarctic-penguin-species). I have included these in my jupyter notebook.

## Research

Research Documents:
 
* [Palmer Penguins Intro](https://allisonhorst.github.io/palmerpenguins/articles/intro.html) . This article details some facts about the palmer penguins, it also gives advice on importing the dataset and shows some formula on how to analyse the data.
 
* [Penguin Species](https://oceanwide-expeditions.com/blog/meet-all-6-antarctic-penguin-species) . This article explains about the different types of species and we learn about the general characteristics of the penguins. 

* [Long Term Ecological Research Network]( https://lternet.edu/) This explains the work done by this network. 

* [Palmer Station](https://en.wikipedia.org/wiki/Palmer_Station) - This article details where it is, what it does, how many people work there and the research that is carried out there.  

* [Statistics by Jim](https://statisticsbyjim.com/basics/discrete-vs-continuous-data/) . This website explains clearly the difference between categorical and continuous variables.

* [Data Types](https://www.w3schools.com/python/python_datatypes.asp). W3 schools details the different data types with examples of list, strings, booleans,integers etc. You can test these on the website. 


## Comparisons

This section mentions some projects that I read and compared to my project. I also got some ideas from these on different graphs I could use.

* [Rpubs](https://rpubs.com/TEHoule/PalmerPenguinPlayground) - Published by Taylor 19.01.2023. This project had similar ideas to mine in displaying the correlation of the palmer penguins. They pull in the dataset and describe it. They start to build up the scatterplot using ggplot, they use different shapes and colours to show different visualisations. They do a line of best fit . They show a facet grid. Overall, the conclusion is similar to mine, quote"We have concluded that there is a strong positive correlation between the flipper length and the body mass of the penguins in the given data set. Furthermore, we have confirmed that this correlation is found across all three species . We created multiple visualization to support these findings and provided information on how these visualizations were created and used to support the analysis".

* [Github Allison Horst](https://allisonhorst.github.io/palmerpenguins/articles/intro.html#highlights) - This shows an example of a scatterplot of the relationship between flipper length and body mass, though variables are on different axis, the distribution is similar and the correlation is similar. Citation:Horst AM, Hill AP, Gorman KB (2020). palmerpenguins: Palmer ,Archipelago (Antarctica) penguin data. R package version 0.1.0. doi:#>   10.5281/zenodo.3960218.


## References

These are some of the many articles I researched to help me learn how to do visualisations and calculate the correlation between the two variables selected.

* [Artwork by Allisonhorst citation](https://allisonhorst.github.io/palmerpenguins/articles/art.html) - Citation for artwork.
* [Quick Guide to Pandas](https://pandas.pydata.org/docs/user_guide/10min.html) - A quick guide on some of the uses of Pandas from describing data to removing null values.
* [GeeksforGeeks missing values](https://www.geeksforgeeks.org/count-nan-or-missing-values-in-pandas-dataframe/) - understanding the impact of missing values.
* [Venngage Barcharts vs Histograms](https://venngage.com/blog/bar-charts-vs-histograms/#:~:text=Although%20histograms%20and%20bar%20charts,of%20variables%20in%20a%20dataset) - blog on when to use either bar chart or histogram
* [Geeksfor Geeks Histograms](https://www.geeksforgeeks.org/interpretations-of-histogram/) - Interpretations of Histograms
* [W3Schools matplotlib](https://www.w3schools.com/python/matplotlib_pyplot.asp) - how to plot using matplotlib
* [W3Schools histograms](https://www.w3schools.com/python/matplotlib_histograms.asp) - how to plot histograms.
* [Investopedia Correlation Coefficient](https://www.investopedia.com/terms/c/correlationcoefficient.asp) - understanding the correlation coefficient.
* [Wikipedia Correlation Coefficient](https://en.wikipedia.org/wiki/Pearson_correlation_coefficient) describes the linear relationship between x and y. It ranges from −1 to 1. If the value is close to +1 it implies that  if the data points are on a line as the x increases, the y also increases. If the value is close to – 1 , it implies a line where y increases while x decreases.
* [Investopedia](https://www.investopedia.com/terms/l/linearrelationship.asp) - Explains that a linear relationship can only consist of two variables
* [Real Python](https://realpython.com/visualizing-python-plt-scatter/)- This articles shows you how to do a scatterplot and how to change shapes and colours.
* [Facet Grids](https://www.geeksforgeeks.org/python-seaborn-facetgrid-method/) - I seen the idea for the facet grids in some of the research documents , particularly the Rpubs project above and I researched how to do it using geeksforgeeks.
* [Disable warnings](https://www.geeksforgeeks.org/how-to-disable-python-warnings/) - This shows how to stop showing warnings that appear for plots etc.
* [Seaborn](https://seaborn.pydata.org/generated/seaborn.pairplot.html) - This shows pairplots using all the numerical variables in the palmer penguin dataset.
* [Seaborn](https://seaborn.pydata.org/generated/seaborn.kdeplot.html) - Explanation and examples of different kernal density plots.
* ChatGPT - This was used to tidy up and make some improvements on a few of the plots.
* [GGPlots](https://bookdown.org/ggiaever/r4ds-solutions/data-visualize.html) - Comparison to other work, building on ggplots.



## That's All Folks, Thanks for Reading, I hope you enjoyed learning about the Palmer Penguins.

![PalmerPenguins](https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png)