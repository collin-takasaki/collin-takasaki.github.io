---
layout: project
type: project
image: images/cosmoslogo.png
title: COSMOS
permalink: projects/COSMOS
# All dates must be YYYY-MM-DD format!
date: 2017-08-10
labels:
  - C++
  - Bitbucket
  - JSON
summary: Altered the JSON format used in COSMOS
---

[COSMOS](http://http://cosmos-project.org/) (Comprehensive Open-architecture Solution for Mission Operations Systems) is a system designed for communicating and controlling single objects or groups of objects.  By using COSMOS, telemetry data is passed between Agents (objects which collect, process, transmit, and receive data) or commands can be sent out and queued.  The COSMOS system is mainly designed with small spacecraft in mind, however, it can be used for many other different kinds of crafts.  

In the source code of COSMOS, the format that is used to transmit telemetry data is JSON (JaveScript Object Notation).  The previous version of the JSON that was used sent every name-value pair as a separate entity.  My goal was to change it to a more proper JSON format that would increase the compatibility of COSMOS with other third-party software.  
 
