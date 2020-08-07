# A Study of employment rates for programmers across countries

### Table of Contents

1. [Prerequisites and Installation](#Prerequisites)
2. [Motivation](#motivation)
3. [File Description](#files)
4. [Conclusion](#conclusion)
5. [Detailed Results](#results)
6. [Acknowledgments](#licensing)

## Prerequisites and Installation <a name="Prerequisites"></a>

This code runs with Python version 3.* and requires some libraries, to install theses libraries you will need to execute: </br>
` pip install -r requirements.txt `

Stackoverflow’s 2018 and 2019  Developer Surveys are also required and can be found [here](https://insights.stackoverflow.com/survey). </br>

To move the downloaded files to the specific folder, you can execute. </br>

1. Stackoverflow’s 2018 data </br>
` mv survey_results_public.csv What-are-the-countries-with-the-highest-number-of-employed-programmers/inputs/2018/survey_results_public.csv `</br>

2. Stackoverflow’s 2019 data </br>
` mv survey_results_public.csv What-are-the-countries-with-the-highest-number-of-employed-programmers/inputs/2019/survey_results_public.csv `</br>

## Motivation <a name="motivation"></a>

This project was made for an an Udacity Nanodegree project. My aim was to compare data in Stackoverflow's 2018 and 2019 surveys to find answers to the following questions:</br>
1. What are the countries with the highest percentage of employed programmers? </br>
2. What are the most common contracts offered? </br>
3. What are the top programming languages used at work? </br>

## File Description <a name="files"></a>

**project.ipynb**: Python code containing my analysis. </br>
**input/2018/survey_results_public.zip**: Zip containing Stackoverflow's 2018 Annual Developer Survey data. </br>
**input/2019/survey_results_public.zip**: Zip containing Stackoverflow's 2019 Annual Developer Survey data. </br>

## Conclusion <a name="conclusion"></a>
In brief, the answers to the above question have been:
* America and India are the easiest countries to find a job as a developer
* Freelancer and part-time jobs are extremely unpopular in the IT sector and we are most likely to find a job as a full-time employee.
* While older programming languages like JavaScript, HTML and CSS are still dominating the market, relatively younger ones ​​like Python have been steadily emerging.

## Detailed Results <a name="results"></a>
If you would like to read more details around how I've reached those conclusions, the results of my analysis are discussed [here](https://medium.com/@marco.altamura88/what-are-the-countries-with-the-highest-percentage-of-employed-programmers-b65b29ed9be4)

## Acknowledgements<a name="licensing"></a>
This project makes use of the following external resources:

Stackoverflow’s 2018 and 2019 Developer Surveys which can be found [here](https://medium.com/@marco.altamura88/using-pyspark-to-predict-sparkifys-users-churn-rate-5e105d7fcdc0).
