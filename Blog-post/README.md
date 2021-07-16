# Data Scientist Nanodegree: Project 1 - Write A Data Science Blog Post

This first project is about creating a blog post and an associated Github repository:

* Come up with three to five questions you are interested in answering.
* Extract the necessary data to answer these questions.
* Perform necessary cleaning, analysis, and modeling.
* Evaluate your results.
* Share your insights with stakeholders.

The data used for this project are from the Stack Overflow surveys for the years 2018, 1019 and 2020, found [here](https://insights.stackoverflow.com/survey)

This repository is one deliverable of the project and the other is [this](https://medium.com/@cliatas/how-will-your-salary-develop-as-you-grow-as-a-developer-721e3e2542f) blog post.

## Environment

The development environment used for working with the project's jupiter notebook was created on a Windows 10 pc, with:

* Installed [Python 3.8.10](https://www.python.org/downloads/release/python-3810/)
* Installed [Miniconda windows 64-bit for Python 3.8](https://docs.conda.io/en/latest/miniconda.html)
* A virtual environment created with the required libraries: `conda create -n dsenv python=3.8 numpy matplotlib pandas jupyter seaborn`

The libraries used for running the jupyter notebook for this project are:
* numpy
* pandas
* matplotlib
* seaborn
* jupyter

Stack Overflow data are not included in the repository. To run the notebook, please create a folder `data` in the same level as this readme file and after downloading the data from Stack Overflow, save the corresponding year's data with the names: `survey_results_public_18.csv`, `survey_results_public_19.csv`, `survey_results_public_20.csv`.

## Files

This part of the repository contains the files for the first project in the [Data Science nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025).

`Blogpost_analysis.ipynb` is the jupiter notebook containing the code for the analysis.
`README.md` is this file containing relevant information and directions for using the jupyter notebook.

## Motivation

For this project data from the Stack Overflow yearly survey were used for the years 2018, 2019 and 2020. These years were selected as the three most recent years with available data to identify possible trends and make comparisons among these from year to year. The questions that motivated this study are:

1. What are the most active age groups? This refers to the age groups (18-24, 25-34, etc.) with the most responders per year and a comparison from year to year.
2. Does there appear to be any trend in the salary related to age groups? Identify the trend, identify highest paid age groups and how the trend developes during three years 2018 - 2020.
3. Is there any trend in the work hours per week among the age groups?
4. Do the average weekly work hours show any association with the average salary per age group?

## Results

Data analysis produced the following results for the above questions respectively:

1. For all the years 2018 - 2020 analyzed the three age groups covering the range 18-44 years old (18 - 24, 25 - 34, 35 - 44), are the most active representing around 90% of the total responses.
2. There is a linear-like increase in the average salary among the different age groups, with the younger age groups having less salary on average than the older groups. This holds true for all three years.
3. Work hours per week, were analyzed for 2019 and 2020, as 2018 dataset does not include this information. For the two years, there appears to be a trend were the older age groups have more work hours on average than the younger ones.
4. Data analysis for the two years 2019 - 2020 shows that a larger salary means more work hours and that older age groups are paid more but also work more hours. The age group 45 - 54 years old in 2019 seems to be an exception, having on average less work hours than the previous younger age group (35 - 44), which might be coincidental and could be worth investigating more given additional years' data.

## Presentation

Please read the related article with results presentation [here](https://medium.com/@cliatas/how-will-your-salary-develop-as-you-grow-as-a-developer-721e3e2542f).
