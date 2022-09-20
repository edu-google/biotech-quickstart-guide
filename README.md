# BioTech Quickstart Guide
BioTech QuickStart guide for all things related to Networking, IAM, BigQuery (Data Warehousing & Data Lake) &amp; Vertex AI (Machine Learning & Artificial Intelligence):

## Overview

This repo contains several distinct Terraform projects each within their own directory that must be applied separately, but in sequence.


### [1. Network](https://github.com/edu-google/biotech-terraform-google-network/)

This stage utilizes Terraform and includes step by step instructions to setup [Newtorking](https://cloud.google.com/docs/terraform/get-started-with-terraform) within your environment. For step by step guide, please refer [README-Networking](https://github.com/edu-google/biotech-terraform-google-network/blob/main/README.md).


### [2. IAM](https://github.com/edu-google/biotech-teraform-google-iam/)

This is a collection of submodules that make it easier to non-destructively manage multiple IAM roles for resources on Google Cloud Platform. For step by step guide, please refer [README-IAM](https://github.com/edu-google/biotech-teraform-google-iam/blob/main/README.md).

This is a collection of submodules that make it easier to non-destructively manage multiple IAM roles for resources on Google Cloud Platform:
[Artifact Registry IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/artifact_registry_iam), [Audit Config](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/audit_config), [BigQuery IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/bigquery_datasets_iam), [Billing Accounts IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/billing_accounts_iam), [Custom Role IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/custom_role_iam), [Folders IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/folders_iam), [KMS Crypto Keys IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/kms_crypto_keys_iam), [KMS_Key Rings IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/kms_key_rings_iam), [Organizations IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/organizations_iam), [Projects IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/projects_iam), [Pubsub Subscriptions IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/pubsub_subscriptions_iam), [Pubsub Topics IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/pubsub_topics_iam), [Service Accounts IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/service_accounts_iam), [Storage Buckets IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/storage_buckets_iam), [Subnets IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/subnets_iam), [Secret Manager IAM](https://github.com/edu-google/biotech-teraform-google-iam/tree/main/modules/secret_manager_iam)


### [3. BigQuery](https://github.com/edu-google/biotech-terraform-google-bigquery)

This module allows you to create opinionated Google Cloud Platform BigQuery datasets and tables.
This will allow the user to programmatically create an empty table schema inside of a dataset, ready for loading.
Additional user accounts and permissions are necessary to begin querying the newly created table(s).
For step by step guide, please refer [README-BigQuery](https://github.com/edu-google/biotech-terraform-google-bigquery/blob/main/README.md).


### [4. Vertex AI](https://github.com/edu-google/biotech-terraform-google-vertexai)

A set of Jupyter Notebooks demonstrating cutting edge GCP Artificial Intelligence (AI) capabilities




