# Renewable Electricity Growth Explorer

## Authors

- [Author #1 name and GitHub username]
- [Author #2 name and GitHub username]

## Project Description

This project explores how renewable electricity generation has changed over time across selected countries. It uses publicly accessible annual data from Our World in Data. Users can choose countries and a year range through a Python interface. The program calculates changes in renewable electricity generation and visualizes comparisons over time. The goal is to make renewable energy growth easier to explore.

## Project Outline/Plan

### Interface Plan

We plan to build a [Flask web app / Tkinter GUI] with a home screen for choosing countries, years, and analysis options, and a results screen for displaying summaries and charts. Planned controls include country selectors, start and end year selectors, a metric selector, chart options, and buttons to load, compare, and reset results. We will check that the final interface has at least 10 interactive widgets.

### Data Collection and Storage Plan — Author #1

Author #1 will download annual renewable electricity data from Our World in Data’s [electricity data page](https://ourworldindata.org/grapher/electricity-mix?frequency=annual&metric=generation&source=renewables). The program will save a local CSV copy in the repository, select the fields needed for country and year comparisons, and handle missing values.

### Data Analysis and Visualization Plan — Author #2

Author #2 will calculate total change and year-over-year growth for each selected country. The program will display a line chart comparing generation over time and a chart ranking countries by growth over the selected period.
