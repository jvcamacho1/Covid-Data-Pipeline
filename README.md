# Covid-Data-Pipeline

This repository contains a simple example of a data pipeline using Databricks that processes and presents data related to COVID-19 infections in the USA. The pipeline consists of several stages, each of which is performed using Python and PySpark in separate notebooks. The pipeline is executed using the Databricks workflow, which allows for the automation and scheduling of tasks.



<p align="center">
  <img src="https://github.com/jvcamacho1/Covid-Data-Pipeline/blob/main/Images/Pipeline.jpg?raw=true" alt="Pipeline Image"/>
</p>

# Pipeline Stages
The pipeline consists of the following stages:

 1. **Data Ingestion:** In this stage, raw data related to COVID-19 infections in the USA is collected from various sources and consolidated into a single dataset.

 2. **Data Cleaning:** In this stage, the data is cleaned and standardized to ensure consistency and accuracy.

 3. **Data Transformation:** In this stage, the cleaned data is transformed to create additional features and enrich the dataset.

 4. **Data Visualization:** In this stage, the data is visualized using the Folium library, which creates an interactive map of all states in the USA, showing the number of COVID-19 cases and deaths.
<p align="center">
  <img src="https://github.com/jvcamacho1/Covid-Data-Pipeline/blob/main/Images/Mapa.jpg?raw=true" alt="Pipeline Image"/>
</p>
Each stage generates an intermediate file that is stored in Parquet format for greater efficiency. The raw data is the unprocessed data. The bronze data is the cleaned and standardized data, the silver data is the transformed and enriched data, and the Gold Data is the vizualization data.

# How to Use
To use this pipeline, follow these steps:

1. Clone the repository to your local machine.
2. Open each notebook in the pipeline folder and run the code in the order specified above.
3. View the final output in the data visualization stage, which displays an interactive map of COVID-19 infections in the USA.

# Conclusion
This COVID-19 data pipeline is a simple example of how to use Databricks to process and visualize data. It can be customized and adapted to work with different datasets and pipelines. We hope that this example serves as a starting point for your own data projects.



