# Databricks 
- Databricks offers LakeFlow , an End to End data engineering solution for delivering high quality data for downstream analytics, AI and operational applications
## LakeFlow Connect
- Efficient ingestion connectors for enterprise applications, databases, cloud storage, message buses and local files.
## Apache Spark 
- A framework for building batch and streaming data pipelines using sql and python
## Lakeflow jobs 
- Workflow automation that orchestrates data processing workloads and coordinates multiple tasks withing complex workflows.

# What is LakeFlow Connect.
1. Traditional Data Ingestion Challenges.
   - Multiple data sources requires their own set of tools and solutions
   - Various sources use various connectors.
   - third party tools and in-house solutions create complexity
   - The result is increased operational overhead, inconsistent governance and fragmented observability
2. lakeflow Connect.
   - With lakeflow connect, we can build efficient ingestion pipelines entirely within databricks.
   - Databricks offers simple setup and maintenance along with unified orchestration, observability and governance.
   - All within the Databricks data intelligence platform.
<img width="727" height="423" alt="image" src="https://github.com/user-attachments/assets/fd16f70e-80a5-4ad4-b4b0-bed3dc6bb80a" />

3. Key benefits of LakeFlow connect. 
   - Lakeflow connect provides built-in connectors.
<img width="763" height="397" alt="image" src="https://github.com/user-attachments/assets/ad365b6a-e5a3-4ac3-8282-a9ec3d8dc1c6" />
4. LakeFlow connect Connectors overview
   - Lakeflow Connect Provides 3 categories.
      - Manual Upload
      - Standard Connectors
      - Managed Connectors
   <img width="770" height="580" alt="image" src="https://github.com/user-attachments/assets/ce8b14f3-5967-47a9-8f81-e09bc3999d61" />
# Ingestion Methods. 
- There are three types of Ingestion Methods.
  - Batch Ingestion
    - <img width="581" height="549" alt="image" src="https://github.com/user-attachments/assets/86255134-6cf4-45b3-91d8-6da31b3d7c62" />
  - Incremental Batch Ingestion
    - <img width="573" height="759" alt="image" src="https://github.com/user-attachments/assets/17e3c28b-04e7-40fa-b118-f585f10fbb26" />
  - Streaming Ingestion
    - <img width="570" height="660" alt="image" src="https://github.com/user-attachments/assets/e4488d5b-8866-441c-8052-d3f0db2b5e49" />

# Delta Lake Review
- Delta lake delivers open, reliable and scalable data management for lakehouse,
  empowering you to ingest data from external sources.
- And manages it across **Bronze(raw), Silver(cleaned), and Global(curated)** layers.
1. Ingesting Data into Delta Lake.
   - Ingest files from **external data sources** like cloud object storage into **Delta Lake as Delta Tables**
     <img width="753" height="274" alt="image" src="https://github.com/user-attachments/assets/933b67ba-823b-4198-a560-ac6299b9bd75" />
2. Delta Table Components Overview
   

     


