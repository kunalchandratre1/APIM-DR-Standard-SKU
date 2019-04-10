# APIM-DR-Standard-SKU
This repository highlights step by step guide for achieving DR in Azure API Management Standard SKU.

API Management (APIM) helps organizations publish APIs to external, partner, and internal developers to unlock the potential of their data and services. Businesses everywhere are looking to extend their operations as a digital platform, creating new channels, finding new customers and driving deeper engagement with existing ones. API Management provides the core competencies to ensure a successful API program through developer engagement, business insights, analytics, security, and protection. You can use Azure API Management to take any backend and launch a full-fledged API program based on it.
Azure API Management as of today offered in various pricing sku with various features – 
1.	Consumption 
2.	Developer
3.	Basic
4.	Standard
5.	Premium.
When you onboard API M as a part of your API story for all of your Enterprise application; this component becomes mission critical. As a best practice we should also configure Disaster Recovery (DR – multi region deployment) for API Management. 
API M DR is by default provided as a service in Premium sku. However at the same time the capacity or workload support by premium sku is massive. Therefore premium sku also comes with premium price. Most of the enterprise needs are observed to get satisfied by BASIC or STANDARD pricing tier. As of today as a benchmarking API M with STANDARD tier support approx. 2500 req/ seconds per unit. STANDARD tier can have upto 4 units. Means total number of requests that can be served by STANDARD API M can go upto 10000 req/ sec. This is massive scale and satisfies most of the Enterprise requirements. However STANDARD sku do not provide DR pre-configured. This proposes bigger challenge for organizations who are betting big on API M. 
This document provides step by step document for configuration of DR for API M STANDARD sku along with architecture. Hope this document will help to address the concern of API M DR in Standard mode. Refer to workd document for detailed information in this repository.

