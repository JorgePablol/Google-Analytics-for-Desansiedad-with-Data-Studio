# Data Analysis Desansiedad (March 2021)
An analysis I did to the google analytics of desansiedad. Desansiedad is a company that provides online anxiety treatment for spanish speakers.

# Results: Final report [here](https://datastudio.google.com/reporting/61f04c52-93e3-4ec5-969a-719304c32849)

# Engineering:
1. Google Data Studio: Applied many filters to engineer the data.
2. Python: Using the typical libraries I engineered the data, see the documents [here](https://github.com/JorgePablol/Data-Analysis-Desansiedad/blob/main/Desansiedad%20(1).ipynb)

* Sorry if it looks a bit confusing, I tried to describe the process well, but as soon as I was jumping too many times from data studio to google colab it was difficult to describe exactly the process.

# Visualization and Reporting:
* The entire viz and reporting was done entirely in google data studio and you can see the [results](https://datastudio.google.com/reporting/61f04c52-93e3-4ec5-969a-719304c32849)

# Tools and libraries:
* Python 3.7
* Google Colab (Jupyter Notebook)
* Google Analytics
* Google Data Studio
* Excel
* Pandas
* Numpy
* Matplotlib

# How:
1. I got access to their google analytics then I connected the google analytics to google data studio.
2. I started analysing what kind of data they have in google analytics.
3. They had historical data from august 2020 until the present, at the time march was starting so I decided to close it to february 2021.
4. The data engineering was made in google data studio, and python (pandas, numpy, maplotlib), I also did some engineering in excel deleting some columns and rows when it was needed.
5. Started to plot dimension by dimension (audience, acquisition, behaviour, conversions) first plotting as a table and then selecting the best visualization.
6. After plotting the best visualization I downloaded the csv to take it to pandas and use the describe() method to have a statistical description on some datasets.
7. I focused on detailed visualizations, they must have the same color logic on the entire presentation.
8. Improved visualizations and descriptive text with highlighted important words.
9. Analysed the project as a whole and started to create a story on how customers consume desansiedad.
10. Prepared the presentation formally and presented it to the marketing team.
