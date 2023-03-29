# Covid-Data-Pipeline

In this repository, there is a simple example of a data pipeline using Databricks that processes and presents data related to COVID-19 infections in the USA.

![Screenshot](https://github.com/jvcamacho1/Covid-Data-Pipeline/blob/main/Images/Pipeline.jpg)

All stages were performed using Python and PySpark, and each stage was done in a different notebook. The pipeline is executed using the Databricks workflow.

Each stage generates an intermediate file that is stored in Parquet format for greater efficiency, where each intermediate file is the result of processing raw data that is identical to the consumed data. Bronze data is standardized and cleaned, while silver data has undergone transformations and enrichment.

Finally, there is a data visualization stage using the Folium library, which is an interactive map of all states in the USA, showing the number of COVID-19 cases and deaths.


