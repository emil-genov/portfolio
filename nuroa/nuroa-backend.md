---
tags: [oracle, mysql, mongodb, spring, lucene, ibatis, jmx, jms, spring-mvc, java-cache]
employer-code: nuroa
employer: Nuroa
project: Nuroa Backend
layout: project
timespan: Jan 2011 - Jun 2012
id: 17
role: Senior Software Developer
excerpt: Nuroa is an vertical search engine centred around property buy/sell, rent and vacation homes. Backend part of it, is responsible for crawling, parsing, transforming and summarising all data site operates on
---
Nuroa is an vertical search engine centred around property buy/sell, rent and vacation homes. Backend part is responsible for crawling, parsing, transforming and summarising all data that site operates on. Consuming huge documents (XML feed files of sizes > 2 GB), it has to be really memory efficient and need to provide robust operation regardless of processor or I/O overloading.

There are two types of data acquisition:
* **From cooperating sites** we get feeds in different file formats, mostly in XML format which are parsed and stored as internal representation in our databases
* **From sites which don't offer feeds** we utilise our own web-crawler that uses templates to allow us to capture the property listing data.

#### Highlights
* Highly parallel feed parsers
* Minimal resource usage
* Monitoring and controlling CPU and I/O usage
* Full text search through Lucene

### Technologies used
* ORACLE DB for operative data
* MySQL for standing data
* MongoDB for listing content
* Spring
* Lucene
* IBATIS
* JMX
* JMS
* Spring MVC
* Java Cache
