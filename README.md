Ntxuva Open311 SMS (beta)
=======


Introduction
-----

This Drupal module enables users to submit Ntxuva reports through SMS.

Ntxuva-Open311-SMS handles requests from Telerivet Webhook API, evaluates the data and generates reports if everything is ok.

Requirements
-----
* A content to work as translator: from Location codes to one of lat & long or address_string or address_id (Georeport v2)
* A content to work as translator: from Problem Code to service_code (Georeport v2)
* An Open311 Georeport v2 endpoint
* Telerivet account (ours is working with an Android to provide a local number for users in Maputo to send us SMS)

Features
----
As it is implemented, Ntxuva Open311 SMS will:
* Report new issues through SMS using the Open311 API
* Check status of report by service_request_id

Getting Started
----
1.

How it works
----
1.

To-Do
---
1. Explain how it works and getting started
2. Work on the semantic analysis of SMS
4. Enhance SMS workflow
3. Include validations of settings
3. Clean messy code

Requirements
-----
* A content to work as translator: from Location codes to one of lat & long or address_string or address_id (Georeport v2)
* A content to work as translator: from Problem Code to service_code (Georeport v2)
* An Open311 Georeport v2 endpoint
* Telerivet account (ours is working with an Android to provide a local number for users in Maputo to send us SMS)

Features
----
As it is implemented, Ntxuva Open311 SMS will:
* Report new issues through SMS using the Open311 API
* Check status of report by service_request_id
