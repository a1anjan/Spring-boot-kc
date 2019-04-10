postgressSQL:
  - Open source relational database management system.

Run PSQL commandline console and enter details to get postgres-# promt

Command help:
# \help <command>  --to get help of any command
# ABORT [ work | transaction  -- abort current transaction
# ALTER CONVERSION name RENAME TO new_name 
# ALTER DATABASE 
# ALTER DOMAIN
# ALTER FUNCTION

Create database :
#create database <database_name>

CREATE DATABASE userdb
    WITH 
    OWNER = postgres
    ENCODING = 'UTF8'
    CONNECTION LIMIT = -1;

COMMENT ON DATABASE userdb
    IS 'testing userdb ';

View database
#\l

connect database:
\c <database name>


Quit from postgress command promt
#\q

Drop database:
# drop database <database name > 

------
pom.xml 

spring-boot-starter-jdbc artifact will give all the spring jdbc related jars

org.postgresql.postgresql will have the dependency of postgres jdbc driver in runtime.

-----


