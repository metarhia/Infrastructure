## Layered Data Storage Module

From hot to cold types of the data

1. Local RAM  
2. Redis cache
3. Postgres 
4. File storage
5. Analytics

## Local RAM

Should be calculatad upon start and constantly used by all processes running on the same machine for super hot parts of data.

## Redis cache

There are no available alternative to redis for this purpose, considering multiple types of data, speed of data access and manipulation, and large quantity of best practices to use it. Especially, with additional Redis modules - there are claims that those modulas are not free, but I didn't find any obstacles to attach them inside docker container. Tarantool and VoltDB have comparable advantages, but far less information, technical support, and examples of implemetation (including enormous software systems).

## Postgres

There are multiple self claimed alternatives to good old Postgres, including multiple relational, NoSql and column databases. However, right configured Postgres (Read/Write separation) in conjunction with TimescaleDB is enabled to the most wide number of data types for enormous amount of transactions (I was assured by industry top professionals that up to 1M users - there is no worry).


## File storage

Cold data storage using the most effective file management systems, such as ZFS (?)

## Analitycs

Snowflake
Vertica
