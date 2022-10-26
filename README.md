<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Strong Random Password Generator
*Damian Borsiak & Jaime Sastre*

*[DA FT Oct 2022, Paris 24/10/2022]*

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description

Our Goals:
- Identify countries with the highest and lowest poverty average rate between 2010 and 2020 in the EU.
- Compare the accuracy between our indicator and an external - existing one.

## Rules

Get the data through API Wrapper with Python.
https://data.worldbank.org/
4 tables as variables
GDP per capita per country($);
Expenditure on health care (%);
Unemployment rate (%);
Violence (per 100.000 people).
 LEFT JOIN on MySQL to get our poverty indicator.
Exporting data of an external indicator.
https://data.oecd.org/inequality/poverty-rate.htm
LEFT JOIN on MySQL to have a table with both:
internal_poverty_indicator
external_poverty_indicator

poverty = - GDP - Health + Unemploy + Violence

x1 = (x-min(x))/(max(x)-min(x))  || To normalize values.

## Workflow
1. Research
2. Project Planning
3. Action
4. Review of created project
5. Project Presentation

## Organization
We were working together on each aspect of the project.

We have used:
1. Jira software for planning with its Roadmap / Backlog / Board functionalities
2. https://www.diagrams.net/ to creat Flow Chart
3. Google Slides for presentation


## Links

[Repository](https://github.com/Borysdb/Project_2_Python_SQL_Poverty.git))
[Slides](https://docs.google.com/presentation/d/1Pk-ncCLN4VEUqhV0i_fegl1On6bcxgd0GCyXWudoFEk/edit?usp=sharing)
