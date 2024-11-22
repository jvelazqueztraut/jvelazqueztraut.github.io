---
layout: post
title: 'CAPI Gateway at Meta'
date: 'Nov 2021'
tag: 'Cloud Infrastructure | Kotlin | Vertx'
---

Core development contributor to **CAPI Gateway**, a cloud-based solution for sending advertising events via server-to-server communication. This product, targeted at thousands of advertisers, is designed to handle **millions of events per second**, providing a scalable and efficient way to process large volumes of advertising data.

![CAPI Gateway Architecture]({{ site.url }}/projects/capi-gateway/CAPI-gateway-architecture.png)

### Features:
- **High-Performance Architecture**: Built using [Vert.x](https://vertx.io/), enabling low-latency, high-throughput event processing.
- **Cloud Native Deployment**: Runs on AWS, with a streamlined **one-click deployment process** and robust scalability.
- **User-Friendly Maintenance**: Includes a web-based interface for configuration and monitoring, ensuring seamless usability for non-technical users.
- **Enterprise-Grade Reliability**: Designed to support mission-critical advertising operations for Meta's extensive client base.

![CAPI Gateway UI]({{ site.url }}/projects/capi-gateway/CAPI-gateway-ui.png)

As part of the **core development team**, I was responsible for:
- Developing critical backend functionalities using **Kotlin** and **Vert.x** to optimize event processing.
- Collaborating on system architecture to ensure reliability and scalability for millions of events per second.
- Took ownership of the observability workstream for the first year of product development.

More product details [here](https://www.facebook.com/business/help/387152639648383) and technical details [here](https://developers.facebook.com/docs/marketing-api/conversions-api/guides/gateway/).