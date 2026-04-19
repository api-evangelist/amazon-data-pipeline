# Amazon Data Pipeline

AWS Data Pipeline is a web service that helps you reliably process and move data between different AWS compute and storage services, as well as on-premises data sources, at specified intervals. With AWS Data Pipeline, you can regularly access your data where it is stored, transform and process it at scale, and efficiently transfer the results to AWS services such as Amazon S3, Amazon RDS, Amazon DynamoDB, and Amazon EMR.

## APIs

### AWS Data Pipeline API

The AWS Data Pipeline API provides a web service for processing and moving data between different AWS compute and storage services as well as on-premises data sources at specified intervals.

- **Base URL:** https://datapipeline.amazonaws.com
- **Documentation:** https://docs.aws.amazon.com/datapipeline/
- **OpenAPI:** [openapi/amazon-data-pipeline-openapi.yml](openapi/amazon-data-pipeline-openapi.yml)

**Tags:** Data Processing, ETL, Workflows

## Artifacts

| Type | Count | Location |
|------|-------|----------|
| OpenAPI Specs | 1 | [openapi/](openapi/) |
| JSON Schemas | 16 | [json-schema/](json-schema/) |
| JSON Structures | 16 | [json-structure/](json-structure/) |
| Examples | 16 | [examples/](examples/) |
| JSON-LD Contexts | 1 | [json-ld/](json-ld/) |
| Spectral Rules | 1 | [rules/](rules/) |
| Vocabulary | 1 | [vocabulary/](vocabulary/) |
| Naftiko Capabilities | 2 | [capabilities/](capabilities/) |

## Features

- **Data-Driven Workflows** — Define complex data processing workflows with activities, data nodes, schedules, and preconditions using a declarative pipeline definition.
- **Multi-Service Integration** — Move and transform data between Amazon S3, Amazon RDS, Amazon DynamoDB, Amazon Redshift, and Amazon EMR in a single pipeline.
- **Flexible Scheduling** — Schedule pipeline runs at fixed intervals (hourly, daily, weekly) or trigger them based on data availability preconditions.
- **Automated Retry and Failure Handling** — Configure automatic retries for failed activities with configurable retry intervals, timeout settings, and failure notifications.
- **On-Premises Data Support** — Process data from on-premises databases and file systems using the Data Pipeline Task Runner agent installed locally.
- **EMR Integration** — Launch and manage Amazon EMR clusters as pipeline resources to run Hive, Pig, and MapReduce jobs as part of data workflows.
- **Pipeline Versioning** — Manage active and latest pipeline definition versions, enabling updates to running pipelines without disrupting current execution.

## Use Cases

- **Daily ETL Workflows** — Schedule daily extraction, transformation, and loading of data from relational databases into S3 or Redshift for analytics processing.
- **Log Processing Pipelines** — Process application and server log files from S3 using EMR activities to generate aggregated reports and analytics datasets.
- **Database Migration** — Migrate data between on-premises databases and AWS managed database services using scheduled pipeline activities.
- **Data Lake Ingestion** — Automate the ingestion and transformation of raw data into structured formats in S3 data lakes for downstream analytics.
- **Cross-Region Data Replication** — Replicate DynamoDB tables or S3 data across AWS regions using scheduled pipeline copy activities for disaster recovery.

## Integrations

- **Amazon S3** — Primary data node type for reading input data and writing output data in pipeline ETL activities using S3DataNode.
- **Amazon EMR** — Managed Hadoop/Spark cluster resource for running large-scale data processing activities including Hive, Pig, and MapReduce jobs.
- **Amazon RDS** — Relational database data node for SQL-based data extraction and loading between RDS instances and S3 or Redshift.
- **Amazon DynamoDB** — NoSQL data node for importing and exporting DynamoDB table data in pipeline activities for batch processing workflows.
- **Amazon Redshift** — Data warehouse target for loading processed pipeline output data for business intelligence and analytics queries.
- **AWS Glue** — Modern alternative managed ETL service that can complement or replace Data Pipeline for serverless data transformation workflows.
- **Amazon CloudWatch** — Monitor pipeline execution status, set up alarms for pipeline failures, and track activity completion metrics.

## Resources

- [Portal](https://aws.amazon.com/datapipeline/)
- [Documentation](https://docs.aws.amazon.com/datapipeline/)
- [Getting Started](https://aws.amazon.com/datapipeline/getting-started/)
- [Pricing](https://aws.amazon.com/datapipeline/pricing/)
- [FAQ](https://aws.amazon.com/datapipeline/faqs/)
- [GitHub Organization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/datapipeline/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Terms of Service](https://aws.amazon.com/service-terms/)
- [Privacy Policy](https://aws.amazon.com/privacy/)

## Maintainers

- **Kin Lane** — kin@apievangelist.com
