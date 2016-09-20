# cics-java-liberty-jaxrs

RESTful service for CICS TSQ browsing using Liberty and JAX-RS


The following Java source components are supplied in the src directory in this repository.

## Java package com.ibm.cics.wlp.devworks.jaxrs.web
Tsq - RESTful TSQ browser
TsqConfig - IBMRestServlet configuration class

## Pre-reqs

* CICS TS V5.1 or later, due to the usage of the getString() methods.
* Java SE 1.7 or later on the z/OS system
* Java SE 1.7 or later on the workstation
* Eclipse with WebSphere Developer Tools and CICS Explorer SDK installed

## Configuration

The sample  code can be added to a dynamic web project and deployed into a CICS Liberty JVM server as a web archive (WAR).

## Reference

More information about this sample can be found at the following tutorial on the CICS [developer center] (https://developer.ibm.com/cics/2016/03/11/java-for-cics-developing-restful-web-services-in-liberty-with-jax-rs)



