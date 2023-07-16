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

---

If you want to support the work I do, please consider donating to me on one of these platforms:

[<img alt="liberapay" src="https://img.shields.io/badge/-LiberaPay-EBC018?style=flat-square&logo=liberapay&logoColor=white" />](https://liberapay.com/stevesteacher/)
[<img alt="kofi" src="https://img.shields.io/badge/-Kofi-7648BB?style=flat-square&logo=ko-fi&logoColor=white" />](https://ko-fi.com/stevesteacher)
[<img alt="patreon" src="https://img.shields.io/badge/-Patreon-F43F4B?style=flat-square&logo=patreon&logoColor=white" />](https://www.patreon.com/Stevesteacher)
[<img alt="paypal" src="https://img.shields.io/badge/-PayPal-0c1a55?style=flat-square&logo=paypal&logoColor=white" />](https://www.paypal.com/donate/?hosted_button_id=P9V2M4Q6WYHR8)
