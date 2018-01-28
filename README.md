# spring3mvc
spring3 mvc annotation

1. Spring Framework (Core, MVC & JBDC)

2. Java 1.8

3. Maven 3.3.9

4. Eclipse IDE (Mars2)

5. MySQL 5.1

DB :
CREATE DATABASE 

  IF NOT EXISTS myusers;USE 

    DROP TABLE 

    DROP TABLE IF EXISTS `myusers`.`users`;CREATE TABLE `myusers`.`users` 

                 ( 

                              `username`  VARCHAR(45) NOT NULL, 

                              `password`  VARCHAR(45) NULL, 

                              `firstname` VARCHAR(45) NOT NULL, 

                              `lastname`  VARCHAR(45) NULL, 

                              `email`     VARCHAR(45) NULL, 

                              `address`   VARCHAR(45) NULL, 

                              `phone`     INT NULL, 

                              PRIMARY KEY (`username`) 

                 )
