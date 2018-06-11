# SLIM PHP REST API

SLIM PHP REST API using SLIM PHP framework

with PDO to connect to MySQL.

https://www.slimframework.com

For standard CRUD operations

200 sample records for DB (MySQL) in customers.sql

Set to run from root folder with htaccess (not public folder as usually advised)

so url will be http://example.com/api/customers

and variations thereof.

## Quick Start

Run composer for deps.

Create MySQL database slimapp, then 

table customers with

id int(11) primary key auto increment

then look in file (or screenshots) for others, all just varchars (255)

For dummy data run import as root

mysql -u root -p slimapp < customers.sql  (place it in home folder linux)

## App Info

### Author

P A McGowan

https://webmobapps.com
https://minimallinux.tk

### Version

1.0.0

### License

This project is licensed under the MIT License
