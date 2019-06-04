---
layout: default
title: Overview
nav_order: 1
---
![](docs/assets/index-47bdbe20.png)  
### DigitalPersona Access Management API  
Version 3.1.1  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;**[DRAFT WS04]**

[Download PDF](docs\DP Access Management API.pdf){: .btn }&nbsp; &nbsp; &nbsp; &nbsp; [View Sample  Repo](https://github.com/LenHodgeman/web-enrollment-sample){: .btn }&nbsp; &nbsp; &nbsp; &nbsp; [View Documentation Repo](https://github.com/LenHodgeman/DP-Access-Management-API){: .btn }  

# Overview

This document describes the DPWebDemo.exe sample program,  and the DigitalPersona features that it demonstrates.
## Introduction
The sample program (DPWebDemo.exe) creates a GUI displaying fields and buttons that showcase the primary features of the DigitalPersona Web Enrollment Services API.  

In order to conserve space in this document and make it more readable, screenshots of the GUI are limited to the section of the window under discussion in the text.  

We will begin with the second tab in the UI, *Enrollment*, since generally speaking you will need to first enroll credentials before you can use them for authentication or identification functions on the first tab.  

Although the sample program will function when the associated DigitalPersona Web Enrollment components are installed on either a DigitalPersona LDS Server or DigitalPersona AD Server, the Create User and Delete User elements only work for a DigitalPersona LDS Server.  

Note: By default, most of the user name fields in the sample application are prepopulated with the current (logged on) Windows User name.
## Enrollment tab

![](assets/index-b4e8a83f.png)

### Element descriptions

#### IP Address or host name
**Purpose**: Specifies the IP Address or host name where the DigitalPersona Web Enrollment components have been installed and where the service is currently running.  
**Actions**: Enter the IP Address or host name for the DigitalPersona Web Enrollment service.   
**Results**: There are no obvious UI changes in the sample application. However, the application will not function until the IP Address or host name has been entered.
#### Ping
**Purpose**: Pings the specified IP Address or host name specified at the top of the sample application window.  
**Actions**: Click Ping.  
**Results**: If successful, displays True.
