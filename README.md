# Data Engineering pipeline for analysing Covid trends using Azure data factory

The pipeline ingests data from 2 sources(azure blob storage and ECDC website for Covid data connected via http protocol) into data lake gen2. The data is then transformed in ADF using dataflow and partially through Databricks & HDInsight based on complexity. The entire transformed data is loaded into data lake for building ML models in the future and a subset of the data is pushed into azure sql database for reporting via Power BI. The project also follows various best practices using control flow activities, triggers and monitoring.

![image](https://github.com/srikrishna777k/Azure-Data-Engineering-pipeline-using-data-factory/assets/75556669/6f609455-05e3-4fec-9ad2-2106ceff5bca)
