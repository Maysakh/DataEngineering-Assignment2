# DataEngineering-Assignment2
HW#2: Building AirFlow DAG: Build an AirFlow DAG for all pipelines and filter on United Kingdom (UK).
Using docker-compose to run the following images: 
Mongodb: To load the data.
Airflow: To build the pipelines and using http://localhost:8080 Or http://127.0.0.1:8080 to run the Airflow.
Postgresql: To extract CSV file


Johns Hopkins and COVID-19 data: https://coronavirus.jhu.edu/map.html

The output of the pipelines should be
■ uk_scoring_report.png
![image](https://user-images.githubusercontent.com/100896230/172801992-874cef85-8f2b-4115-b9ae-7c29d241af9a.png)

■ uk_scoring_report.csv
Day	Confirmed	Deaths	Recovered	Active	Incident_Rate	Case_Fatality_Ratio
11/9/2020	2.7E-07	0.0E+00	3.6E-04	0.0E+00	7.7E-04	0.0E+00
11/9/2020	1.9E-05	7.0E-05	2.2E-02	5.0E-06	1.3E-02	5.5E-01
11/9/2020	6.5E-06	8.0E-06	8.4E-03	0.0E+00	9.1E-03	1.8E-01
![image](https://user-images.githubusercontent.com/100896230/172802055-096fde55-c365-48af-8cca-baaba7e5d5e3.png)

■ PostGreSQL table uk_scoring_report
