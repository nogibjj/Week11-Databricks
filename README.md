[![CI](https://github.com/nogibjj/python-template/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/python-template/actions/workflows/cicd.yml)
## Week 11: Data Pipeline with Databricks
- Goals :
1. Create a data pipeline using Databricks
2. Include at least one data source and one data sink

## Jupyter Notebook
- [Data Pipeline with Databricks](Songs Notebook.ipynb)

## Steps
### Ingest the raw data

![](Results/raw_data.png)

### Prepare the raw data

![](Results/prepared_data.png)

### Query the transformed data

> Which artists released the most songs each year?

![](Results/sql_query1.png)

> Find songs for your DJ list

![](Results/sql_query2.png)

### Create a Databricks job to run the pipeline

![](Results/pipeline.png)


### Result

![](Results/result.png)

## Reference

1. https://github.com/nogibjj/python-template
2. https://docs.databricks.com/en/getting-started/data-pipeline-get-started.html