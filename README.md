# Taxi Service

<a name="Overview"></a>
## Overview
Taxi Service is a web application that allows you to store information about
drivers / manufacturers / or cars in a database. With this service you can
write / delete / read / update data in the database

<a name="Use-cases"></a>
## Use cases

* Log in / Log out
* Register
* Add a new car
* Add a new manufacturer
* Add a driver to the car
* Delete driver from the database
* Show all drivers 
* Show all cars
* Show all cars for current user
* Show all manufacturers

<a name="Used-Technologies"></a>
## Used Technologies

* Java 11
* Custom Injector
* Apache Tomcat (v9.0.50)
* MySQL
* JDBC
* HttpServlet and Filter
* HTML, CSS, JSP, JSTL
* Maven

<a name="Project-structure"></a>
## Project structure
Project implemented refers to an n-tier structure and has three layers:

1. DAO layer
2. Service layer
3. Controllers layer

<a name="Application-startup"></a>
## How to run this project

1. Install MySQL
2. Install Tomcat 9.0.50 or 9.0.63 version
3. Clone it using one of the "Code" options, which is more suitable for you
4. To initialize the database run this file "src/main/resources/init_db.sql"
   WARNING: It will drop an existing database with name "taxi", and create new.
5. Go to the ConnectionUtil class located in "src/main/java/taxi/util" and add your url to database, login, password. (Be careful with adding URL. You might need to add a Timezone to it too)
6. Add configuration: Tomcat Server/local, application context set to "/".
7. Run the project.