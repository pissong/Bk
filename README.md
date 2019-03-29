# Bk
ShoppingCart_Demo
===============

Used Tech
---------
Tomcat 7.0
JDK : 1.7
Spring MVC:4
Mysql :5
Eclipse (JBoss Developer studio)
Hibernate :4

find below dtls in the application propertie file (path:bk\src\main\resources)
++======================================
#Database related properties
database.driver=com.mysql.jdbc.Driver
database.url=jdbc:mysql://localhost:3306/bk
database.user=root
database.password=bb

Run Below script in mySql bk database
===================================
create table Product(prodId integer auto_increment not null,
prodCode varchar(20) not null,
price varchar(20) not null,
quantity varchar(20)not null,
name varchar(20),
size varchar(20) not null,
status varchar(3),
primary key (prodId));

===============================================

open "bk project" in the patn write cmd and press enter
1. run this commd  mvn clean install
2. u can import the war file into ur server or run directly if ur server is embedded 

