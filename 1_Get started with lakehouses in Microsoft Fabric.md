# Explore end-to-end analytics with Microsoft Fabric

## Fabric 
Fabric is a unified software-as-a-service (SaaS) platform where all data is stored in a single open format in OneLake.

## OneLake 
OneLake is built on Azure Data Lake Storage (ADLS) and supports various formats, including Delta, Parquet, CSV, and JSON

![image](https://github.com/user-attachments/assets/32a3e917-0a40-4516-a43e-7e3a6c2b9eb9)

## Workspaces

In Microsoft Fabric, workspaces serve as **logical containers that help you organize and manage your data, reports, and other assets**. They provide a clear separation of resources, making it easier to control access and maintain security.

Each workspace has its **own set of permissions**, ensuring that only authorized users can view or modify its contents. This structure supports team collaboration while maintaining strict access control for both business and IT users.

Workspaces allow you to manage compute resources and **integrate with Git for version control**. You can optimize performance and cost by configuring compute settings, while Git integration helps track changes, collaborate on code, and maintain a history of your work.

## Administration and governance
Fabric's OneLake is centrally governed and open for collaboration. Data is secured and governed in one place, which allows users to easily find and access the data they need. Fabric administration is centralized in the Admin portal.

In the admin portal you can manage groups and permissions, configure data sources and gateways, and monitor usage and performance. You can also access the Fabric admin APIs and SDKs in the admin portal, which can automate common tasks and integrate Fabric with other systems.

The OneLake catalog helps you analyze, monitor, and maintain data governance. It provides guidance on sensitivity labels, item metadata, and data refresh status, offering insights into the governance status and actions for improvement.

# Explore data teams and Microsoft Fabric 

## Traditional roles and challenges 
In a traditional analytics development process, data teams often face several challenges due to the division of data tasks and workflows.

Data engineers process and curate data for analysts, who then use it to create business reports. This process requires extensive coordination, often leading to delays and misinterpretations.

Data analysts often need to perform downstream data transformations before creating Power BI reports. This process is time-consuming and can lack the necessary context, making it harder for analysts to connect directly with the data.

Data scientists face difficulties integrating native data science techniques with existing systems, which are often complex, and makes it challenging to efficiently provide data-driven insights.

## Evolution of collaborative workflows
Microsoft Fabric simplifies the analytics development process by unifying tools into a SaaS platform. Fabric allows different roles to collaborate effectively without duplicating efforts.

**Data engineers** can ingest, transform, and load data directly into OneLake using Pipelines, which automate workflows and support scheduling. They can store data in lakehouses, using the Delta-Parquet format for efficient storage and versioning. Notebooks provide advanced scripting capabilities for complex transformations.

**Data analysts** can transform data upstream using dataflows and connect directly to OneLake with Direct Lake mode, reducing the need for downstream transformations. They can create interactive reports more efficiently using Power BI.

**Data scientists** can use integrated notebooks with support for Python and Spark to build and test machine learning models. They can store and access data in lakehouses and integrate with Azure Machine Learning to operationalize and deploy models.

**Analytics engineers** bridge the gap between data engineering and analysis by curating data assets in lakehouses, ensuring data quality, and enabling self-service analytics. They can create semantic models in Power BI to organize and present data effectively.

**Low-to-no-code users** and **citizen developers** can discover curated datasets through the OneLake Hub and use Power BI templates to quickly create reports and dashboards. They can also use dataflows to perform simple ETL tasks without relying on data engineers.

# Enable and use Microsoft Fabric

## Create items with Fabric workloads
After you create your Fabric enabled workspace, you can start creating items in Fabric. Each workload in Fabric offers different item types for storing, processing, and analyzing data. Fabric workloads include:

**Data Engineering**: Create lakehouses and operationalize workflows to build, transform, and share your data estate.
**Data Factory**: Ingest, transform, and orchestrate data.
**Data Science**: Detect trends, identify outliers, and predict values using machine learning.
**Data Warehouse**: Combine multiple sources in a traditional warehouse for analytics.
**Databases**: Create and manage databases with tools to insert, query, and extract data.
**Industry Solutions**: Use out-of-the-box industry data solutions.
**Real-Time Intelligence**: Process, monitor, and analyze streaming data.
**Power BI**: Create reports and dashboards to make data-driven decisions.
