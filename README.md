# ADF pipeline type HDinsight cluster
In this Sample I am creating a test pipeline using Azure Data Factory with Spark hdinsight activity to do some basic transformations in python and then write the output to a CSV.

1) The source file in this sample can be any json object with some meaning full data
2) Basic transformations and mappings to be used in python3 to create data frames and combine them.
3)Final output to write it into an csv and save it in a AZURE Blob storage (you can use any storage, I am using blob just to make use of AZURE services)
4) For this use case i have used Jupyter Notebook to build my logic, I prefer Jupyter just because it makes it easy for me to follow TDD.


In this example you would require to create a Azure data factory pipeline and the relevant information is found in the below link
https://docs.microsoft.com/en-in/azure/data-factory/introduction





