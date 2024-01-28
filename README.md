In this project I am using Tokyo-Olympic data to process in Azure platorm.

1. load data into github repo
   
3. create ADF pipeline to load all 5 files from github to ADLS Gen 2 (Azure data lake storage gen 2 account).
pipeline = olympic-data-ingestion
   
5. use databricks to perform transformation on data loaded in previous step and store transformed data into ADLS Gen 2 under new folder.
   notebook = Tokyo-Olympic-Transformation

6. create tables in synapse workspace using datalake.

7. load data from synapse analysis into power BI and create intractive reports.
