📊 World SQL Analysis
📌 Description

This project analyzes the classic world.sql database (MySQL) which contains information about countries, cities, and languages around the world.
The analysis is performed using Python (Pandas, Seaborn, Matplotlib, SciPy) and connected to the MySQL database through SQLAlchemy.


- Objectives

Compare the average population of cities in Asia vs Europe.

Test whether the average city population differs significantly across continents.

Analyze the distribution of official vs non-official languages across continents.


- Methods

Welch’s t-test → comparing two groups (Asia vs Europe).

ANOVA / Kruskal–Wallis test → comparing more than two groups (continents).

Chi-Square Test of Independence → analyzing categorical data (languages).

Visualization → boxplots, histograms, stacked bar charts for better interpretation.


 - Results

Asia vs Europe → Cities in Asia are on average larger than in Europe. The result is statistically significant, but the effect size is very small.

Across Continents → There are significant differences in average city populations among continents.

Languages → The proportion of official vs non-official languages is not evenly distributed across continents (e.g., Africa is dominated by non-official languages).


- Tools Used

Python 3.11

Pandas, NumPy, Matplotlib, Seaborn, SciPy

MySQL, SQLAlchemy
