# Building Batch Data Pipelines on GCP

## Overview

Data pipelines typically fall under one of the Extract-Load, Extract-Load-Transform or Extract-Transform-Load paradigms. This course describes which paradigm should be used and when for batch data. Furthermore, this course covers several technologies on Google Cloud Platform for data transformation including BigQuery, executing Spark on Cloud Dataproc, pipeline graphs in Cloud Data Fusion and serverless data processing with Cloud Dataflow. Learners will get hands-on experience building data pipeline components on Google Cloud Platform using QwikLabs.

## Key Concepts

### Introduction

- Introduce course agenda

### Introduction to Batch Data Pipelines

- Review different methods of loading data into your data lakes and warehouses: EL, ELT and ETL
- Discuss about data Quality considerations and when to use ETL instead of EL and ELT

### Executing Spark on Cloud Dataproc

- In this module we will review the parts of the Hadoop ecosystem.
- How to lift and shift your existing Hadoop workloads to the cloud using Cloud Dataproc.
- Why we should consider using GCS instead of HDFS for storage
- How to optimize your Cloud Dataproc jobs

### Manage Data Pipelines with Cloud Data Fusion and Cloud Composer

- Discuss how to manage your data Pipelines with Data Fusion and Cloud Composer.
- Recall that Cloud Data Fusion allows data analysts and ETL developers to wrangle data and build pipelines in a visual way.
- Learn how Cloud Composer can help to orchestrate the work across multiple GCP services.

### Serverless Data Processing with Cloud Dataflow

- Understand how to decide between Cloud Dataflow and Cloud Dataproc for processing data pipelines
- Understand the features that customers value in Dataflow
- Discuss core concepts in Cloud Dataflow
- Review the use of Dataflow templates and SQL
