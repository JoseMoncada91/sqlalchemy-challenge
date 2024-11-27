SQLAlchemy Challenge by Jose Moncada (11/26/2024)
This project focuses on building a Flask API to analyze and expose historical weather data for a fictional Hawaiian climate study. Using Python, SQLAlchemy, Flask, and SQLite, it demonstrates skills in data engineering, analysis, and API development.

Overview
Key objectives of the project include:

Database Setup: Connecting to an SQLite database (hawaii.sqlite) and using SQLAlchemy ORM to map and reflect tables.
Data Analysis:
Analyzed precipitation data for the last 12 months.
Identified the most active weather station.
Extracted temperature trends for specific date ranges.
Precipitation analysis queries were supported by ChatGPT.
Flask API: Developed routes to expose weather data:
/: Welcome message and list of endpoints.
/api/v1.0/precipitation: Precipitation data for the last 12 months.
/api/v1.0/stations: List of weather stations.
/api/v1.0/tobs: Temperature observations from the most active station.
/api/v1.0/<start>: Min, max, and average temperature from a start date.
/api/v1.0/<start>/<end>: Temperature stats for a specified date range.
This repository demonstrates proficiency in database management, querying, and API design while integrating data analysis workflows.
