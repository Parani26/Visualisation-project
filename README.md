View Markdown: https://parani26.github.io/Visualisation-project/

Project Overview

This project investigates how eclipse visibility varies across different states and regions in the United States. 
Using eclipse observation datasets from the TidyTuesday release dated 2024-04-09, the project focuses on two major eclipse events: the annular solar eclipse on October 14, 2023 and the total solar eclipse on April 8, 2024. 
The main objective is to use data visualisation techniques to identify geographic and temporal patterns in eclipse visibility across the US.

Data Sources

The datasets were obtained using the tidytuesdayR package and consist of four eclipse datasets: eclipse_annular_2023, eclipse_total_2024, eclipse_partial_2023, and eclipse_partial_2024. 
Each dataset includes location-level information such as latitude, longitude, and state, along with the recorded times of eclipse phases at each observation location.

Methodology

The data preparation process involved standardising column formats and converting eclipse timing variables into hms objects for consistent time-based processing. 
All datasets were combined into a single dataset to support cross-event comparison, and the data was reshaped into a long format where eclipse phase types are stored as categorical variables and timings are stored as observations. 
Summary statistics were computed to understand the number of unique locations, average coordinates, and timing ranges across eclipse categories.

Visualisations

Three main visualisations were developed to support analysis. 
A geographic scatter map was used to visualise where eclipse observations occurred across US states, allowing a comparison between the 2023 annular and 2024 total eclipse. 
A ridgeline plot was used to illustrate how eclipse phase timings vary across states, highlighting differences in the temporal distribution of eclipse events. 
A pyramid barplot was created to compare eclipse observation counts across states for 2023 and 2024 while distinguishing between different eclipse types.
