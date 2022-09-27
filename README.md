# database-connection-cpp
Simple database connection and display in C++

# NOTICE
For a more up-to-date tutorial, watch this one instead: https://youtu.be/WlEFQPvKUPo

---

This is a simple database connection using C++ and the mysql.h header. I created this on Parrot OS and used mariadb, so you may need to tweak a few things before you can use it yourself... You can watch the tutorial here: https://youtu.be/cSZvq7Kv6_0


Here is a database table if you're here from the tutorial:
```sql
CREATE TABLE `tblUsers` (
	`id` INT NOT NULL AUTO_INCREMENT,
	`name` varchar(30) NOT NULL,
	`surname` varchar(50) NOT NULL,
	`email` varchar(255) NOT NULL UNIQUE,
	`password` varchar(255) NOT NULL,
	PRIMARY KEY (`id`)
);
```
