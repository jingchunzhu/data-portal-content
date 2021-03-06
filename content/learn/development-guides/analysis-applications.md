---
path: "/learn/development-guides/analysis-applications"
date: "2018-05-03"
title: "Analysis Applications"
subTitle: "Technical resources to support the development and integration of your analysis applications."
---

# Creating Solutions using the DCP

The Human Cell Atlas Data Coordination Platform holds much potential to support and enrich solutions for single cell genomics. This page highlights resources you can leverage to enable your creativity.

## General Description

We provide several computational solutions to use in building products. We have several REST APIs for programmatic interface, an open metadata schema to leverage, cloud-native pipelines that are portable to multiple environments, and standardized domain specific methodology and visualizations. We provide a growing collection of vignettes as examples of interacting with different aspects of the DCP. After you have made a product interacting with the DCP, please register it with the Data Portal for data hand-off, or list it in our Registry.

## Examples

**Consumer Vignettes** These vignettes highlight the process of certain programmatic tasks that involve the DCP.

[Consumer Vignettes](/learn/development-guides/consumer-vignettes)

## Working with Ingest

**Ingest API** The Ingest Service provides a programmatic API for submitting data. This may be useful, for example, for LIMs integration solutions. This does require authentication and would require contacting the ingest team at [data-help@humancellatlas.org](mailto:data-help@humancellatlas.org).

[Starting point: GitHub Repository Ingest Central (ingest-central)](https://github.com/HumanCellAtlas/ingest-central)    
[GitHub Repository for Ingest API(ingest-broker-api)](https://github.com/HumanCellAtlas/ingest-broker-api)    
[HAL Browser for the Ingest API](http://api.ingest.dev.data.humancellatlas.org/browser/index.html)   

## Learning More About Metadata

**HCA Metadata** The [HCA metadata schema](https://dev.data.humancellatlas.org/learn/metadata/structure) is a curated description of the entities and thier relationships captured in HCA data. The metadata schema is public for review on GitHub. The metadata schema is also extensible and open for changes through pull requests.

[Learn More About Metadata](https://github.com/HumanCellAtlas/metadata-schema/tree/master/docs)   
[Github Repository for metadata schema (metadata-schema)](https://github.com/HumanCellAtlas/metadata-schema)   
[GitHub Repository for the metadata API Library (metadata-api)](https://github.com/HumanCellAtlas/metadata-api)   

## Accessing the Data Store

**Consumer API** Data in the HCA *Data Store* can be accessed programmatically through the consumer API. This interface includes both a REST API end point and a CLI (python).

[Consumer API Swagger](https://dss.integration.data.humancellatlas.org)   
[HCA DCP CLI](https://hca.readthedocs.io/en/latest)   

## Leveraging Pipelines

**Pipelines** Our cloud-native pipelines are created using GA4GH workflow languages (CWL or WDL). On release, these pipelines can be found on Dockstore and during development can be found in GitHub. Our pipelines are modular and one can also reuse the tasks (or tools) that comprise the pipelines; we point to both pipelines and tasks below.

[GitHub Repository for Pipelines (Skylab)](https://github.com/HumanCellAtlas/skylab)   
[Pipeline Tasks](https://github.com/HumanCellAtlas/skylab/tree/master/library/tasks)   
[Dockstore](https://dockstore.org)   

## Accessing the Matrix Service

**Matrix Service API** The Matrix Service enables the ability to create matrices from underlying data in the DCP. The Matrix Service currently exposes a REST API endpoint. This can be given a manifest of files to combine, that can be polled until the service generates the requested matrix for download.

Matrix Service Description - Coming Soon    
Matrix Service swagger - Coming Soon   

## Finding Packages for Your Solution

**HCA DCP Methods Registry** The Methods Registry contains domain-specific computational methodology and visualization component packages that are standardized in a way we hope enables clear communication and ease of use between the methodologists and engineers.

[Methodology Listing](/analyze/methods/methods)   
[Visualization Component Listing](/analyze/visualization-components)   

## Registering with the Data Portal

**Portal hand-off** The Data Portal provides the ability for portals and other solutions to "register" with the Data Portal. Registration enables users to move from the Data Portal to the registered product as they explore data, which is an excellent way to integrate with the DCP.

Hand-off Description - Coming Soon   
Register for the Hand-off - Coming Soon  

## Listing Your Solution in the Registry

Please list your solution with the registry so our community of scientists knows about it and can easily find it.

[Submit a Portal](https://github.com/HumanCellAtlas/data-portal-content/issues/new?template=submit-portal)    
[Submit a Methodology](https://github.com/HumanCellAtlas/data-portal-content/issues/new?template=submit-method)     
[Submit a Visualization Component](https://github.com/HumanCellAtlas/data-portal-content/issues/new?template=submit-visualization-component)     
