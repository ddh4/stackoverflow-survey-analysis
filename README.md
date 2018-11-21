Please note, the datasets used in this project are too large to be uploaded here on GitHub and can be found [here](https://insights.stackoverflow.com/survey). I renamed the earlier datasets (pre-2017) to be in a consistent format in the notebooks, i.e. the same format of 2017 and 2018. Sorry for the inconvinience!

# Table of Contents
1. [Installation](https://github.com/ddh4/stackoverflow-analysis#installation)
2. [Project Motivation](https://github.com/ddh4/stackoverflow-analysis#project-motivation)
3. [File Descriptions](https://github.com/ddh4/stackoverflow-analysis#file-descriptions)
4. [Results](https://github.com/ddh4/stackoverflow-analysis#results)
5. [Licensing, Authors, and Acknowledgements](https://github.com/ddh4/stackoverflow-analysis#licensing-authors-and-acknowledgements)

# Installation
The libraries necessary are:
- NumPy
- Scikit Learn
- Pandas
- Matplotlib
- Seaborn

All libraries necessary are bundled with Anaconda distribution of Python 3.*..

# Project Motivation

For this project, I was interested in performing an exploratory data analysis of Stack Overflow survey data from 2013-2018, with a focus on popularity in 2018.

The exercise was a data driven approach to business understanding, with a focus on students or people interested in making a career step.
1. The level of formal education reported by developers?
2. How does the level of formal education relate to reported salaries?
3. How does the level of formal education relate to reported job satisfaction?
4. What are the most popular languages in 2018 and their trends over the past 6 years, including forecasts for 2019?
5. What are the most popular roles in the industry and salary distributions?

This repository contains the data preparation, wrangling and visualisation steps which the blog is based on.

# File Descriptions

This repository contains 2 notebooks which discuss the data in more detail and the CRISP-DM process that was followed.
1. Salary and Satisfaction in Formal Education - relating to the first 3 questions posed above.
2. Trend Analysis of Programming Languages and Job Roles - relating to the final 2 questions posed above.

Markdown cells were used to explain the process and decisions made throughout the analysis.

# Results

In our study, we looked at the statistics for the formal education level of developers in industry in 2018, finding that traditional university tracks dominate the user base.
We further explored how formal education level relates to financial compensation and job satisfaction, which showed differences in interquartile ranges that are in line with traditional education tracks, primary school through to university degrees.
We additionally gathered data from 6 years of developer responses and analysed the trend of the top 10 languages in 2018 and included the forecasts for 2019.
We finally looked at the most popular job roles by percentage of the userbase in tech and then calculated the salary distributions of each.

The blog post containing the results of our questions is available [here](https://medium.com/@d.d.hamilton/how-far-and-where-should-you-go-to-get-what-you-want-in-a-tech-career-4ed59401fbeb).

# Licensing, Authors, and Acknowledgements
The data is provided to the public by Stack Overflow, available [here](https://insights.stackoverflow.com/survey).
The code in this repository can be used freely.
