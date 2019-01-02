---
layout: post
title:  "eventdriven.ai - Scalable and Extensible platform for realtime AI decisions"
permalink: /product-overview/
author: sriram
categories: [ Realtime, data, processing, eventdriven ]
image: assets/images/rdp.jpg
featured: true
---
eventdriven.ai (formerly Real time Data Processing hub) is an extensible and scalable event data processing AI framework that provides real-time decisions and can create adhoc analytics, dashboards, scorecards and reports. The eventdriven.ai platform consists of four basic components event driven framework, rules engine, data storage and Analytics. The event driven framework supports plugin for capturing data from multiple data sources containing both structured and unstructured data like xml, csv, json, attributes, image, text, etc....

Core components of the eventdriven.ai framework are:
+ Event Driven Framework
+ Intelligent Rules Engine
+ Data Storage
+ Analytics

# Event Driven Framework
> Used to capture events across multiple systems. The product will support multiple data formats. Events can be published over HTTP/HTTPS, File Upload, Queues, Stream processing using Apache Kafka.

# Intelligent Rules Engine
> Used to process the events with the configured rules. This module will contain Rules Engine as a backend and a front end to configure the rules. The rules engine application uses existing data, historical data and configured meta data for processing.

# Data Storage
> All events that match the rules, requiring analytics will be persisted in a data storage. Bigdata data store will be used to persist information about the rules.

# Analytics
> Analytics framework will provide role-based dashboard, reports and analytics. Updates to dashboard will be on real-time basis. User may configure webhooks for actions based on the rules.