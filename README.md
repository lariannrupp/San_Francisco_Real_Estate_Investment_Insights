# San_Francisco_Real_Estate_Investment_Insights

<img width="489" alt="Screenshot 2022-02-02 234925" src="https://user-images.githubusercontent.com/95719899/152294757-0d061ebe-c715-4214-a46c-18771b6463db.png">

---

The purpose of this exercise is to use aggregation, interactive visualizations, and geospatial analysis, to demonstrate how to find properties in the San Francisco market that are viable investment opportunities.

Please note that this exercise uses static csv's from 2010-2016 San Francisco census data. As such, any insights gained from this exercise may not necessarily hold true for current trends and should not be considered as financial advice. The exercise is merely a demonstration of how to visualize real estate analysis with Python libraries and tools.


## Technologies

**A Python 3.9.7 (ipykernal) in JupyterLab** was used to write this notebook.


Additional Python libraries are imported into the start of the app: 


<img width="434" alt="Screenshot 2022-02-02 234555" src="https://user-images.githubusercontent.com/95719899/152294791-d9c2a670-ed11-4610-912b-41bcb78cd9a5.png">



---

## Installation Guide

To use the app, from the Github repository, download:
- **san_francisco_housing.ipynb** Jupyter file 
- **Resources** folder that contains two csv files which the program uses

Use either Terminal or GitBash to run the app in a conda dev environment. 
To enter a conda dev environment, type
'conda activate dev'

You may need to install the PyViz Ecosystem in Terminal or GitBash.
Install the PyViz packages by using the conda install command as follows:
> conda install -c pyviz hvplot geoviews

Confirm the installation of all the PyViz packages by running the following commands:
> conda list hvplot
> conda list geoviews

To run the app, navigate to the root directory, which contains **san_francisco_housing.ipynb** and the **Resources** folder adjacent to one another, and then type
'jupyter lab'



---

## Usage

As you run through the exercise, observe how I analyzed San Francisco Real Estate Investment Opportunities through the following steps:

*Calculate and plot the housing units per year.

* Calculate and plot the average prices per square foot.

* Compare the average prices by neighborhood.

* Build an interactive neighborhood map.

* Compose a data story.

Based on the visualizations that I created, I answered the following questions:

> How does the trend in rental income growth compare to the trend in sales prices? Does this same trend hold true for all the neighborhoods across San Francisco?
> 
> What insights can I share about the potential one-click, buy-and-rent strategy? Do neighborhoods exist that I would suggest for investment, and why?


---

## Contributors

This exercise was based on a challenge problem from UC Berekely Fintech Bootcamp Module 6, accessed on 2022.02.02. 

For any questions, please reach out to me on [LinkedIn](https://www.linkedin.com/in/lari-rupp-5baa49153/)

---

## License

Creative Commons Zero
