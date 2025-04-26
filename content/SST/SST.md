---
title: SST
tags:
  - SST
  - Serverless
  - Node
  - Typescript
---

[SST](https://sst.dev/) is my go to framework to pretty much release anything. It is an [[Glossary#IAC]] framework. Under the hood it uses [Pulumi](https://www.pulumi.com/) but provides a very nice level of abstraction to make deploying to the cloud MUCH easier. 

Typically I default to AWS but have also experimented with GCP cloud run.

Components within SST are broken down into constructs which are an abstraction on the required cloud components to build and host services in the cloud using mostly serverless architecture.
