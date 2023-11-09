---
layout: default
title: API Documentation using Markdown
permalink: /
---

# Introduction

This section is intended to give the reader an overview of how to deliver a common search experience, medical cost and out of pocket cost lookup, as well as detailed provider information. This overview covers inputs and outputs for each endpoint, and relationships between the endpoints. For further detail on each endpoint, navigate to that specific endpoint's in-depth page.

## Protocol
All APIs must be accessed using HTTPs.  All data is returned as JSON.

## Versioning
At the current time, version 1 of the API is supported.

## Table of contents

* [Authorization](api-docs/auth.md)
* [Users](api-docs/users.md)
* [Plan Benefits](api-docs/benefits.md)
* [Providers](api-docs/providers.md)
* [RXBrands](api-docs/rx.md)
* [Medical Procedures](api-docs/procedures.md)
* [Search](api-docs/search.md)


## Data Models

Data models are visual representations of an enterprise’s data elements and the connections between them. By helping to define and structure data in the context of relevant business processes, models support the development of effective information systems. They enable business and technical resources to collaboratively decide how data will be stored, accessed, shared, updated and leveraged across an organization.

This section depicts the major model classes and how they interact.

![alt text](/api-docs/images/model.png)
