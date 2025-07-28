# Project Description

This is a Java-based web application built with Spring MVC, Spring Security, and Spring Data JPA. It features user account management and integrates with MySQL, Memcached, RabbitMQ, and Elasticsearch for data storage, caching, messaging, and search. The frontend uses JSP and the application runs on Tomcat, with Maven for build management.

The project has been successfully lifted and shifted to Amazon AWS. It is deployed on four EC2 instances behind a Load Balancer, with Auto Scaling enabled for high availability and scalability. DNS management is handled using Route 53, ensuring reliable access and traffic distribution.

A MySQL database dump is provided for easy setup. Please refer to the instructions below for importing





Prerequisites
JDK 17 or 21
Maven 3.9
MySQL 8
Technologies
Spring MVC
Spring Security
Spring Data JPA
Maven
JSP
Tomcat
MySQL
Memcached
Rabbitmq
ElasticSearch
Database
Here,we used Mysql DB sql dump file:

/src/main/resources/db_backup.sql
db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
mysql -u <user_name> -p accounts < db_backup.sql




# Prerequisites
#
- JDK 17 or 21
- Maven 3.9
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql
