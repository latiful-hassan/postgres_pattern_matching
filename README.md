# postgres_pattern_matching_basics

## Table Creation & Data Import

- I will be using Covid-19 data downloaded form Kaggle that I cleaned for brevity in Excel
- Below are the queries used to create the table and copy the data from the csv file:

![](https://github.com/latiful-hassan/postgres_pattern_matching/blob/main/covid_data_screenshots/covid_data_table.png)

- Here is an excerpt of the data:

![](https://github.com/latiful-hassan/postgres_pattern_matching/blob/main/covid_data_screenshots/covid_data_select.png)

## Pattern Matching

### Wildcards

- **%**:

![](https://github.com/latiful-hassan/postgres_pattern_matching/blob/main/covid_data_screenshots/covid_data_wildcard.png)

- **_**:

![](https://github.com/latiful-hassan/postgres_pattern_matching/blob/main/covid_data_screenshots/covid_data_underscore.png)

### Regular Expressions

- **Starts With (^)**:

![](https://github.com/latiful-hassan/postgres_pattern_matching/blob/main/covid_data_screenshots/covid_data_start_with.png)

- **Alternation (|)**:
  * This gives values of Laos, Latvia and Sri Lanka

![](https://github.com/latiful-hassan/postgres_pattern_matching/blob/main/covid_data_screenshots/covid_data_alternation.png)


- **Repetition (+, *):

![](https://github.com/latiful-hassan/postgres_pattern_matching/blob/main/covid_data_screenshots/covid_data_repetition.png)
