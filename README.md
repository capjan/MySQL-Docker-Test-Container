# MySQL Test Database

This repository contains a docker orchestration to create a test environment with a local MySQL Server.

## Requirements

* Up and running Docker Host and docker-compose
* **Do NOT use this Container in production environments** without further configuration!

## Info

* MySQL 5.7

* Connection String: 

  ```tcl
  Server=localhost;Database=db;Uid=user;Pwd=password;
  ```

* Stores the database data in a local folder: **mysql-db**

* Check docker-compose.yml for further information.

* [MySQL image documentation on Docker Hub](https://hub.docker.com/_/mysql)