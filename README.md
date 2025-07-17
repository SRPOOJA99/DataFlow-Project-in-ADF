Project Title: Data Transformation Using Mapping Data Flows in Azure Data Factory (ADF)

Project Overview:

This project focused on building a robust data transformation pipeline using Azure Data Factory (ADF) to process, transform, and store structured data from Azure Blob Storage. The project demonstrates end-to-end data orchestration, starting from data ingestion to transformation and finally to data persistence using Mapping Data Flows.

Key Components & Implementation Details:

Azure Blob Storage Setup:

Created an Azure Storage Account and configured Blob Containers to store raw source data.

Uploaded two structured datasets, representing Customer and Orders tables, into the container for further processing.

ADF Data Flow Development:

Designed and developed a Mapping Data Flow within Azure Data Factory.

Configured Source transformations to read data from the blob storage.

Defined the Sink transformation to load the processed data into the desired destination (e.g., another Blob container, Azure SQL Database, etc.).

Transformation Logic:

Utilized various built-in transformations to clean and shape the data:

Select: Chose only the relevant columns needed for downstream processing.

Filter: Applied conditional filters to eliminate unnecessary or invalid records.

Sort: Ordered data based on specific fields for organized processing.

Join: Merged data from the Customer and Orders tables to create enriched datasets.

Derived Column: Created new fields based on expressions or transformations of existing data.

Conditional Split: Implemented logic-based branching to separate data flows based on defined conditions.

Multi-Stream Integration:

Created multiple parallel data streams within the same data flow pipeline.

Combined and orchestrated these streams effectively to perform complex transformations and dependencies.

Data Output and Storage:

The transformed data was written to a designated destination (e.g., curated zone in Blob Storage or Azure SQL).

Ensured data integrity and quality at the output stage using data preview and monitoring features in ADF.

Outcome:

The project resulted in a fully automated and scalable ETL pipeline leveraging Azure Data Factory’s low-code/no-code Mapping Data Flows. It enabled efficient data preparation and transformation, facilitating improved data quality and usability for downstream analytics and reporting processes.
