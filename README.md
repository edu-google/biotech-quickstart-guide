# BioTech Quickstart Guide
BioTech QuickStart guide for all things related to Networking, IAM, BigQuery (Data Warehousing & Data Lake) &amp; Vertex AI (Machine Learning & Artificial Intelligence):

## Overview

This repo contains several distinct Terraform projects each within their own directory that must be applied separately, but in sequence.

### [1. Network](https://github.com/edu-google/biotech-terraform-google-network/)

This stage utilizes Terraform and includes step by step instructions to setup [Newtorking](https://cloud.google.com/docs/terraform/get-started-with-terraform) within your environment. If you want to refer the step by step guide, please see [README-Networking](./biotech-terraform-google-network/README.md).

### [2. IAM](./biotech-teraform-google-iam/)

This stage utilizes Terraform and includes step by step instructions to setup [Newtorking](https://cloud.google.com/docs/terraform/get-started-with-terraform) within your environment. If you want to refer the step by step guide, please see [README-Networking](./biotech-terraform-google-network/README.md).

This is a collection of submodules that make it easier to non-destructively manage multiple IAM roles for resources on Google Cloud Platform:
* [Artifact Registry IAM](./biotech-teraform-google-iam/modules/artifact_registry_iam)
* [Audit Config](./biotech-teraform-google-iam/modules/audit_config)
* [BigQuery IAM](./biotech-teraform-google-iam/modules/bigquery_datasets_iam)

### [3. BigQuery](./biotech-terraform-google-bigquery/)

This module allows you to create opinionated Google Cloud Platform BigQuery datasets and tables.
This will allow the user to programmatically create an empty table schema inside of a dataset, ready for loading.
Additional user accounts and permissions are necessary to begin querying the newly created table(s).

### [3. Vertex AI](./biotech-terraform-google-vertexai/)

A set of Jupyter Notebooks demonstrating cutting edge GCP Artificial Intelligence (AI) capabilities


The bootstrap step includes:

- The `prj-b-seed` project, which contains:
  - Terraform state bucket
  - Custom Service Accounts used by Terraform to create new resources in GCP
- The `prj-b-cicd` project, which contains:
  - A CI/CD pipeline implemented


