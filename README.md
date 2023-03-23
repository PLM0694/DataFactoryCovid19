# DataFactoryCovid19

Hands on practice, following course: https://www.udemy.com/course/learn-azure-data-factory-from-scratch/ 

Instead of using the outdated data from the course, I decided to pull the new data directly from the ECDC Covid-19 site on Mar 22, 2023: https://www.ecdc.europa.eu/en/covid-19/data

Simple Azure Data Factory pipeline to ingest data into Data Lake.
![ADF Pipeflow](https://user-images.githubusercontent.com/55467236/227068510-34a3c478-bf3c-4835-9cf9-57f98f84f728.jpg)

Since my data was a bit different from the course, I did extra setps such as updating the value 'NA' to zero.
![DFforCasesDeaths](https://user-images.githubusercontent.com/55467236/227365470-6a2f04c4-7184-4085-9803-8849a4c2e90d.jpg)
