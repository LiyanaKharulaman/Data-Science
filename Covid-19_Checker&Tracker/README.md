# COVID-19_Tracker

Introduction
============
COVID-19 third wave has hit Malaysia harder than the first and the second. 2020 Sabah State Election is believed to be one of the factors causing a sudden spike in daily new cases in every state. Ministry of Health (MoH) has been actively updating the healthcare facilities for those who are seeking screening and treatment. It is an ongoing battle, however, the only way to move is forward.

Questions (or Problems)
=======================
- Where is the health facilities for screening and treating COVID-19 cases?
- How many number of COVID-19 active cases in every district?

Motivation
==========
Therefore, this project is intended to:
- provide a predictive symptom checker in order to take further actions.
- provide a Malaysia's map to aid the users in finding screening and treatment for COVID-19.
- provide an interactive visualization in order to potray number of active cases from 26th Sept 2020 – 30th Nov 2020 for every state and district.

Data Science Process
====================
**Data Acquisition**
- Healthcare facilities for screening and treating COVID-19 in every district provided by Ministry of Health.
- Number of COVID-19 active cases in every district provided by State Health Departments (Facebook).

**Data Pre-Processing**
- Imputing missing data by using hot deck imputing method.
- Fetching latitude and longitude of healthcare facilities from Google API to plot the coordinates on the Malaysia's map.

**Data Exploration (EDA)**
- Number of active cases filtered by state and district for a given date from 26th Sept 2020 – 30th Nov 2020.

References
==========
- Leaflet tutorials: https://rstudio.github.io/leaflet/shiny.html
- Shiny Dashboard tutorials: https://rstudio.github.io/shinydashboard/get_started.html
- ShinyThemes: https://rstudio.github.io/shinythemes/
- ShinyApps Icon: https://fontawesome.com/v4.7.0/icons/
