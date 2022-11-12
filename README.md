Portfolio Projects:
-	I developed an ETL pipeline for collecting stocks data from a web source. This pipeline extracts data by scraping web pages through Scrapy and transforms raw data to a clean format through a Spark job. I developed this pipeline as an Airflow DAG for running in Google Cloud by using Cloud Composer, Cloud Dataproc Serverless, and Cloud Storage; all provisioned with Terraform.

    Demo: https://www.youtube.com/watch?v=_ry9udKQZig \
    Repository: https://github.com/hdt94/case-etl-stocks
  
    ![](https://github.com/hdt94/case-etl-stocks/blob/master/etl_stocks.png)

-	I developed a system prototype for monitoring civil infrastructure using IoT/sensing systems. This prototype operates data pipelines developed using Apache Beam and Cloud Dataflow Flex Templates for batch and micro-batch processing of data files from object storage; it serves a React SPA embedding Grafana dashboards; and implements HTTP-based RESTful APIs that use Postgres Cloud SQL and MongoDB. I developed and deployed this system using multiple services from Google Cloud provisioned with Terraform.

    Demo (no audio): https://www.youtube.com/watch?v=vqtL2tFqQ-g \
    Repository: https://github.com/hdt94/monitoreo
  
    ![](https://github.com/hdt94/monitoreo/blob/master/diagram.general.png)

-	I developed an application for visualizing data from a microcredit entity and estimating loan defaulting. This is a multi-page Dash-Plotly application and a single FastAPI endpoint that works with an analytical model (I did the cleaning of raw data while fellows built the model).

    Demo (no audio): https://www.youtube.com/watch?v=7x6vzjNo3O0 \
    Repository: https://github.com/hdt94/ds4a-project
