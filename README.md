# Spotlight on Amazon Elasticsearch Service

## What is Elasticsearch?
Elasticsearch is a search engine based on the Lucene library which uses BM25 under the hood. Apart from being open-source, tt is distributed in nature meaning it can scale quite easily and works with schema-free JSON documents. To learn more about Lucene and opensource Elasticsearch please do look at the detailed [Lucene and Elasticsearch Spotlight by Minreng](https://github.com/tamucse670/2020.spring.spotlight/blob/master/Minreng%20Wu_Lucene%20and%20Elasticsearch_Feb27.ipynb).

## Amazon Elasticsearch Service
AWS Elasticsearch Service is a fully managed service making it easier for developers to deploy Elasticsearch cost effectively at scale. It also provides various security features that you can use to make your APIs secure. The service provides support for open source Elasticsearch APIs, managed Kibana, integration with Logstash and other AWS services, and built-in alerting and SQL querying.

## Benefits
* **Easy to deploy and manage** - Be ready in minutes!
* **Highly scalable and available** - Upto 3 PB data in a single cluster
* **Highly secure** - Isolation using Amazon virtual private cloud (VPC) and encryption
* **Cost-Effective** - pay for what you use
* **Perform search in near real time** - slight latency(~1sec) to index a document

## Disadvantage
1. Elasticsearch does not have multi-language support
2. Works only with JSON unlike Apache Solr which can work with CSV, XML and JSON formats

## Key Concepts
* **Node** - single instance running Elasticsearch
* **Cluster** - a collection of one or more nodes. It is responsible for providing indexing and search capabilities.
* **Index** - a collection of different type of documents and their properties
* **Document** - collection of fields. Basic unit of information that can be indexed.

## Comparison with Relational database

| Elasticsearch | RDBMS |
| ------------- |:-------------:|
| Cluster |	Collection of Database |
| Shard  | Shard      |
| Index  | Database  |
| Type  | Table  |
| Mapping	| Schema |
| Field	| Column |
| Document (JSON Object) |	Row |
| ID	| Primary Key |

## Detailed Notebook
https://nbviewer.jupyter.org/github/aditya30394/Spotlight-on-AWS-Elasticsearch/blob/master/Elasticsearch.ipynb
