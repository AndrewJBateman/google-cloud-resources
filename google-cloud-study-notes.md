# :zap: Google Cloud Architect Certification

Notes on Google Cloud Architect Certification.

## Ch1,2 Basics, Identity & Access Management

* IAM roles (Least privilege principle). For example, testing user knowledge on billing account roles, storage access roles, compute engine role, etc.
* How to list and describe the roles using CLI
* How to filter the roles and members using GCP console

## Ch 9 App Engine

How to deploy applications on App Engine using CLI.
Use cases on App Engine Versions functionality
How to split the traffic between multiple versions in the App Engine.

* [App Engine](https://cloud.google.com/appengine)

## Ch 14 Virtual Private Clouds (Networking)

How to configure firewalls and use cases
Shared VPC
VPC peering vs VPN vs Interconnect
Types of load balancers and use cases

## Ch 3 Projects

How to create projects
Linking projects with the billing accounts
How to list and describe the existing configurations
How to create and manage projects via CLI

## Ch 3 Billing Accounts

Required roles to create and manage the billing accounts
Understanding the relation between Billing accounts & Projects & Organizations

## Ch 4 Compute Engine

The understanding of market place use cases (Ex: If the user wants to deploy functional software packages without having to manually configure the software or Virtual Machine instances)
Auto-scaling types (Selecting best scaling type based on the given scenario)
When to use External IP address (Static external vs Ephemeral external IP)
Importance of metadata and labels
High availability (Spreading the resources across the Global vs Regional)
Understanding Managed and Unmanaged instance groups.
*[Compute Engine](https://cloud.google.com/compute)

## Ch 11 Cloud Storage (Object-based)

When to use different storage classes available in GCP (Ex: Multi-regional vs Regional vs Nearline vs Coldline)
Changing or conversion of storage classes. (Ex: Multi-regional to Nearline, Multi-regional to Coldline, etc)
Automatic deletion of objects and Objects transfer between the different storage classes using lifecycle policies

* [How Google stores massive amounts of data — BigTable](https://medium.com/@avantikadasgupta/how-google-stores-massive-amounts-of-data-bigtable-d67f49bfc40e)

## Ch 7 Kubernetes Engine

The deployment process of a docker file
How to create a docker file and understanding of container registry
Autoscaling in Kubernetes
Working of cluster nodes and services

* [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine)
* [Introduction to Using Google Kubernetes Engine; Explain Like I’m Five! (Part I)](https://medium.com/faun/google-kubernetes-engine-explain-like-im-five-1890e550c099)
* [Kubernetes on GKE : Series Intro](https://blog.mercurie.ng/kubernetes-on-gke-series-intro/)

## Databases

Relational databases: SQL vs Spanner
When to use BigQuery and Cloud Bigtable

## Loading Data Into Storage

## Bigdata Tools

Difference between Dataproc vs Dataperp
Questions based on Pub/Sub use cases and integration with other services
Data Analytics tools use cases

## Image-based Questions: 2 Questions

Provided the sample company cloud architecture diagram with blanks and asked to fill the blanks with suitable GCP services as per requirement demand

## Stackdriver

Importance of [Stackdriver](https://cloud.google.com/monitoring/) in the Google cloud and how it works. Monitors GCP and AWS resources.
Creating and configuring workspaces
How to add projects from different GCP accounts to single Stackdriver account via GCP console

## Abbreviations

* CIDR: Classless inter-domain routing - a set of Internet protocol (IP) standards that is used to create unique identifiers for networks and individual devices.
