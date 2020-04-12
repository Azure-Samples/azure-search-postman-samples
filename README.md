# Postman collections for Azure Cognitive Search

This repository provides Postman collections used in REST API walkthroughs. All collections are saved in JSON, in the V2 collection format.

To use these collections, import them into **Postman**.

## Full-syntax-examples collection

Requests in this collection create indexes using various analyzers, followed by query requests that demonstrate full Lucene syntax, used for suffix and infix wildcard search, partial term search, and other query types.

You must edit this collection to replace placeholder values with an endpoint and API key that is valid for your service.

1. After importing the collection, expand the (`...`) action list and select **Edit**.

2. Enter the search service name and an admin API key. Admin access is required to create and delete objects on a search service. After saving your changes, you can run each request with no further modification.

## Knowledge-store collection

Contains requests for creating and populating an index with hotel reviews data from Kaggle. The collection also includes an indexer and skillset that contains instructions for expressing a knowledge store in Azure Storage.

## Simple-syntaxxexamples collection

Requests in this collection create indexes using various analyzers, followed by query requests that demonstrate simple syntax. 

You must edit this collection to replace placeholder values with an endpoint and API key that is valid for your service.

1. After importing the collection, expand the (`...`) action list and select **Edit**.

2. Enter the search service name and an admin API key. Admin access is required to create and delete objects on a search service. After saving your changes, you can run each request with no further modification.

Most examples are self-explanatory. For the NOT query, see the Boolean operator section for either [simple](https://docs.microsoft.com/azure/search/query-simple-syntax).

## Quickstart collection

Includes 4 requests used to create an index, load documents, search the index, and query system information. Request bodies include JSON documents that provides index and documents.  

## Tutorial collection

This collection provides the same requests as those used to build an AI enrichment pipeline in [Tutorial: Add structure to "unstructured content" using REST APIs](https://docs.microsoft.com/azure/search/cognitive-search-tutorial-blob). 