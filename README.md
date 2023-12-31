﻿# 🎥 BullScreen Cinema app
## Project description:
Simple example of concept web app that follows RESTful API rules and supports user authentication, authorization as well as various CRUD operations. Created using Spring & Hibernate.
___
## Project functionality:
Here is the scheme of this app to better understand its functionality:
[![Cinema_scheme](src/main/resources/Cinema_scheme.png)](src/main/resources/Cinema_scheme.png)
___
## Project's structure:

* config - contains config classes required by Spring & Hibernate
* controller - all http controllers
* dao - classes responsible for crud operations with db
* dto - used for http requests and responses
* exception - custom exceptions
* lib - custom validators for email, password and confirm password
* model - model classes for entities shown in scheme above
* service - classes that are responsible for business logic and connecting dao with controllers
* service/mapper - mappers that are used to parse dto to entity and entity to dto
* util - util class containing date pattern to parse date from json
___
## Technologies:

Java 17, Spring Web MVC 5.3.20, Spring Security 5.6.10, Hibernate 5.6.14.Final, MySql 8.0.22, Tomcat 9.0.71, Maven.

## Installation 💻

Here are the steps to run this app locally:

1. Clone this repository and open it locally.
2. Add all the required configurations to db.properties file in src/main/resources folder.
3. Install Tomcat.
4. Run the app.
5. Connection established! 🎉
