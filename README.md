
# Investigating the delay reasons of TTC

The TTC has a major problem with constant service disruption. However, with the above unsatisfactory experiences, TTC decided to make some unexpected changes after 26 March
- TTC increasing fare to  $3.35.
- Longer wait times for most lines 

Problem statement:

How does the weather affect the TTC service of subway? If not, what is the factor affecting TTC service the most?

![TTC](https://github.com/ktchan33GBC/Datapipline_proj_TTC_weather/blob/main/image/TTC.jpg)


As a Data Engineer, I built a data pipeline project to investiage this issue. 

Project Steps:


- Landing structured data files into DBFS of Databricks with Hive and landing semi-structured data into MongoDB
- Combining both data sources and transforming them into an operational database format
- Using SSIS to transfer operational data into the data warehouse
- Using Spark to summarize the data and prepare it for reporting
- Using Power BI to visualize the data and present it to stakeholders

## Dataset

Structured data:
Toronto Weather  :  Rain and snow CSV format

Semi-structured:
toronto_subway json format



## Screenshots



![Concept Map](https://github.com/ktchan33GBC/Datapipline_proj_TTC_weather/blob/main/image/concept_map.png)


![Pyspark to MongoDB Sample ](https://github.com/ktchan33GBC/Datapipline_proj_TTC_weather/blob/main/image/mongoDB_connection.png)

![Data Visualization Sample](https://github.com/ktchan33GBC/Datapipline_proj_TTC_weather/blob/main/image/ttc%26weather_powerbi_page1.pdf)
## Support

For support, email katsunchanai@gmail.com

## Feedback

If you have any feedback, please reach out to me at katsunchanai@gmail.com


