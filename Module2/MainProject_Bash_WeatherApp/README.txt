Introduction
This project automates the Extract, Transform, Load (ETL) process for weather data, specifically focusing on extracting daily weather forecast and observed weather data for Casablanca, Morocco. It transforms this data into a structured format and loads it into a log file for further analysis by the analytics team.

Scenario
As part of a larger prediction modeling project, this proof-of-concept (POC) initially focuses on monitoring and measuring the historical accuracy of temperature forecasts. The project extracts actual temperature and forecasted temperature for the following day at noon from a specific source for Casablanca.

Data Source
The weather data is sourced from wttr.in, a web service providing weather forecast information. The data is retrieved using the curl command.
