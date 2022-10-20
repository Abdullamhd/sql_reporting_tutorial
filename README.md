# Northwind database for Postgres

Standerd SQL Reporting Tutorial 

## This repo contain the base SQL file for the Northwind database for Postgres
### cloned from 
https://github.com/pthom/northwind_psql

## Table diagram for Northwind database

<img src=ER.png />

## Getting started:
### 1. Install Docker if you don't have it already
### 2. Clone this repo
### 3. Run the following command in the root of the repo:
```
docker-compose up
```
### 4. open the following url in your browser:
```
http://localhost:5050/browser/
```
### 5. login to pgAdmin with the following credentials:
```
email: 
admin@localhost
password:
123456
```
### 6. register a new server with the following credentials:
```
name:postgres
host:db
port:5432
username:postgres
password:postgres
```


