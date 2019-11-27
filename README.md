# Fundamentals of Data Analytics 2019 Assessment #

## Course: Highter Diploma in Data Analytics #
## Module: Fundamentals of Data Analytics #
## Year & Semester: 2019 - 02

## Student: Niamh O'Leary ##
## ID: G00376339 ##

## Introduction ##

Seaborn is a Python data visualisation library based on matplotlib. It provides a high level interface for drawing attractive and informative statistical graphics.[1] High quality visualisations allow for the identifying of trend and building models.

Here is some of the functionality that seaborn offers:

1. A dataset-oriented API for examining relationships between multiple variables
2. Specialized support for using categorical variables to show observations or aggregate statistics
3. Options for visualizing univariate or bivariate distributions and for comparing them between subsets of data
4. Automatic estimation and plotting of linear regression models for different kinds dependent variables
5. Convenient views onto the overall structure of complex datasets
6. High-level abstractions for structuring multi-plot grids that let you easily build complex visualizations
7. Concise control over matplotlib figure styling with several built-in themes
8. Tools for choosing color palettes that faithfully reveal patterns in your data [2]

In machine learning model while training any model you need to first find which features are important or on which features the result is dependent. This can be done using data analysis and data visualization. We’ll learn how to visualize different types of data, and what we can infer from that plot, and when to use them. Seaborn is a library built on matplotlib. It’s easy to use and can work easily with Numpy and pandas data structures. We’ll be using inbuilt dataset provided by seaborn name tips. [3]

Exploratory Data Analysis (EDA) is an approach to analyzing datmanimasets to summarize their main characteristics. It is used to understand data, get some context regarding it, understand the variables and the relationships between them, and formulate hypotheses that could be useful when building predictive models. [4] 

## About the Tips Dataset ##

The tips dataset comes built-in with the Seaborn library. The tips database contains information about the bills paid by the customers at a fictional restaurant. The dataset contains information about people who probably had food at a restaurant and whether or not they left a tip, their age, gender and so on.


## Task ##

This assessment concerns the well-known tips dataset and the Python packages seaborn and jupyter . The project is broken into three parts, as follows.

1. Description: Create a git repository and make it available online for the lecturer to clone. The repository should contain all your work for this assessment. Within the repository, create a jupyter notebook that uses descriptive statistics andplots to describe the tips dataset. 
2. Regression: To the above jupyter notebook add a section that discusses and analyses whether there is a relationship between the total bill and tip amount, and this part is also worth.
3. Analyse: Again using the same notebook, analyse the relationship between the variables within the dataset. You are free to interpret this as you wish — for example, you may analyse all pairs of variables, or select a subset and analysethose. 


## Packages used in this project ##
The following packages were used to run statistical analysis and draw grpahs for this project.

Python https://www.python.org/downloads/

Anaconda https://www.anaconda.com/distribution/ - is the easiest way to perfrom Python data science machine learning on Linux, Windows and Mac OS.

iPython https://ipython.org/ - it an interactive command-line terminal for Python.

Pandas https://pandas.pydata.org/ - pandas is an "open source, BSD-licensed library providing high-performance, easy-to-use data structures and data analysis tool."

Scripy https://pypi.org/project/Scripy/ - which allows the user to run system commands in the same shell through it's main tool *shell.Run().

Numpy http://www.numpy.org/ - is the fundamental package for scientific computing within Python.

Matplotlib https://matplotlib.org/ - is a 2D plotting library within Python within which the user can generate a wide variety of figures, including plots, histograms, scetterplots etc.

Seaborn https://seaborn.pydata.org/ - is a Python data visualisation library based on matplotlib. It provides a high level interface for drawing infromative statistical graphs.

Ploty https://plot.ly/ -  Plotly provides online graphing, analytics, and statistics tools for individuals and collaboration, as well as scientific graphing libraries for Python, R, MATLAB, Perl etc.

Cufflinks https://plot.ly/python/v3/ipython-notebooks/cufflinks/

Scikit-learn https://scikit-learn.org  - Scikit-learn is a simple and effecient tool for data mining and data analysis. 

## Importing packages ##
The above packages can be imported into Python. Use Import function in iPython as follows:

#Import libaries that will be used in this project #

'''import numpy as np'''
'''import pandas as pd'''
'''import matplotlib.pyplot as plt'''
'''import seaborn as sns'''
'''import scikit-learn as sklearn'''

## Importing the data ##
Import the tips.csv file using Seaborn.

## Contents of GitHub Respository ##

The GitHub Respository associated with this project contains the following:
1. Tips databas in .csv format.
2. ReadMe file giving an overview of the project and the project outline.
3. Jupyter Notebook outlining the analysis of the tips.csv database containing python code and description of the analysis.
4. License. 

## References ##

1. www.seaborn.pydata.org
2. https://seaborn.pydata.org/introduction.html 
3. https://towardsdatascience.com/analyze-the-data-through-data-visualization-using-seaborn-255e1cd3948e 
4. https://dev.to/nexttech/how-to-perform-exploratory-data-analysis-with-seaborn-29eo

## Biblography ##

1. Tutorialspoint.com. (2019). Seaborn - Linear Relationships - Tutorialspoint https://www.tutorialspoint.com/seaborn/seaborn_linear_relationships.htm   
2. Tutorialspoint.com. (2019). Seaborn - Facet Grid - Tutorialspoint. https://www.tutorialspoint.com/seaborn/seaborn_facet_grid.htm 
3. Medium. (2019). Analyze the data through data visualization using Seaborn. https://towardsdatascience.com/analyze-the-data-through-data-visualization-using-seaborn-255e1cd3948e 
4. GeeksforGeeks. (2019). Python | Pandas dataframe.info() - https://www.geeksforgeeks.org/python-pandas-dataframe-info/ 
5. GeeksforGeeks. (2019). Python | Pandas dataframe.groupby() - GeeksforGeeks.https://www.geeksforgeeks.org/python-pandas-dataframe-groupby/
6. Valcheva, S. (2019). Bivariate Data Analysis: Examples, Definition, Data Sets Correlation.  Science, and Management. http://intellspot.com/bivariate-data-examples/ 
7. Visualization, D. and Python, B. (2019). A Comprehensive Guide to Seaborn in Python.  https://www.analyticsvidhya.com/blog/2019/09/comprehensive-data-visualization-guide-seaborn-python/ 
8. Pythonbasics.org. (2019). Seaborn Distplot | Python Tutorial.  https://pythonbasics.org/seaborn-distplot/
9. https://medium.com/@julie.yin/understanding-the-data-splitting-functions-in-scikit-learn-9ae4046fbd26 
10. Michael Waskom. Tips data set. https://github.com/mwaskom/seaborn-data/blob/master/tips.csv.
11. McLooughlin, I (2019), course material for 52446 Fundamentials of Data Analysis, GMIT.
12. https://stackabuse.com/using-plotly-library-for-interactive-data-visualization-in-python/
11. http://www.marcelscharth.com/python/visualisation.html
12. https://stackabuse.com/using-plotly-library-for-interactive-data-visualization-in-python/
13. https://github.com/delhiank762/Exploratory-Analysis-of-Tips-Dataset/blob/master/tips%20data%20analysis.ipynb
14. https://www.codementor.io/wajihaurooj/python-seaborn-tutorial-data-visualization-using-seaborn-wpj9qydr2
15. https://www.geeksforgeeks.org/seaborn-distribution-plots/
16. https://www.codespeedy.com/seaborn-module-of-python/
17. https://www.ritchieng.com/machine-learning-linear-regression/
18. https://medium.com/analytics-vidhya/linear-regression-using-python-ce21aa90ade6
19. https://seaborn.pydata.org/tutorial/regression.html
20. https://www.datacamp.com/community/tutorials/understanding-logistic-regression-python
21. https://www.kdnuggets.com/2019/03/beginners-guide-linear-regression-python-scikit-learn.html
22. https://www.edvancer.in/step-step-guide-to-execute-linear-regression-python/
23. https://wellsr.com/python/seaborn-plots-for-python-data-visualization/
24. https.oreilly.com/learning/data-visualization-with-seaborn


## Author = Niamh O'Leary #


