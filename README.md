# Futurice_assignment
Futurice is looking to expand a new office location inside the European Union. The expansion needs to be decided based on two factors:
a) Size of ICT sector in the country
b) Amount of cloud services used in country’s enterprises

Based on the input dataset available the analysis has been performed in the notebook to find out the top list of countries for a new office. 

Input Datasets Available:-- 

1)gdp_data.csv
2)Percentage of the ICT sector on GDP in json-stat format 
3)Percentage of cloud computing services used in enterprises in json-stat format  

The input dataset has been directly used from github url. The input dataset no 2 and 3 has been manually converted to csv by using JSON-stat CSV Exporter and uploaded to filestore location of databricks for further use.

Tech Stack Used:-
1)PySpark
2)Spark SQL
3)Pandas
4)Python

The final dataset has been presented in bar chart to show the top countries for office expansion. One chart shows the top countries for large enterprise, another chart shows the top countries for small enterprise. Based on the two bar charts, the final country name is concluded.
