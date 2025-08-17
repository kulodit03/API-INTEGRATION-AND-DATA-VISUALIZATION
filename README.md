# API-INTEGRATION-AND-DATA-VISUALIZATION

Introduction
This project focuses on the integration and automation of data extraction from the Marvel API using Docker, InfluxDB, and Grafana. The primary goal is to create a real-time data visualization system, leveraging the flexibility and capabilities of these tools.

Table of Contents
Introduction
1 Background
2 Objectives
3 Development and Analysis
4 Visualization in Grafana
5 Conclusions
6 References

Background
To achieve this project, our group utilized the following tools:

APIs: For flexible and integrative data extraction.
Docker: To create consistent and reproducible development environments.
InfluxDB: A time-series database ideal for real-time data monitoring and analysis.
Grafana: An open-source tool for interactive data visualization and analysis.

Objectives
The objectives of this project are:

Extract data from the Marvel API using a Python script.
Store the obtained data in an InfluxDB database.
Visualize the stored data using Grafana.
Automate the entire process using Docker.

Development and Analysis
Automation with Docker
Docker ensures the portability and replicability of the environment by encapsulating the Python script, InfluxDB, and Grafana in independent containers, facilitating orchestration and deployment.

Data Extraction
The Python script performs HTTP requests to the Marvel API, processes the responses, and formats the data for storage in InfluxDB. Error handling and pagination are also managed within the script.

Storage in InfluxDB
InfluxDB is used to store the extracted data. The script connects to InfluxDB, creates the necessary database, and inserts the formatted data into it.

Integration with Grafana
Grafana is configured to use InfluxDB as a data source, allowing the creation of interactive dashboards for real-time data analysis and monitoring.

Visualization in Grafana
Dashboard Creation
Interactive dashboards are designed to display various graphs obtained from the Marvel API data.

