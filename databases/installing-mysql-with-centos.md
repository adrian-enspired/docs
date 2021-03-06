---
title: Installing MySQL with CentOS
subject: MySQL
---

# Installing MySQL with CentOS

## But first...
You will need A limited user with sudo access. For assistance creating one, see [Creating Sudo Users](https://www.thermo.io/how-to/security/creating-sudo-users).

## Method
This method uses the popular MariaDB drop-in replacement for MySQL. Installation is simple using the CentOS package manager, yum. 

Issue:
```shell
sudo yum install mariadb mariadb-server
sudo systemctl enable mariadb
sudo systemctl start mariadb
```
For additional guidance, see [MySQL basics](https://www.thermo.io/how-to/databases/mysql-basics).

**_For 24-hour assistance any day of the year, contact a Thermo Physicist [by email](mailto:physicists@thermo.io) or [through the Client Portal](https://www.thermo.io/login/)._**
