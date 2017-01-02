## #1 [MySQL] mysql.sock not found while login

### Problem Des.
```
mysql -u root -p
Enter Password:
ERROR 2002 (HY000): Can't connect to local MySQL server through socket '/tmp/mysql.sock' (2)
```

### Problem Sol.

Sol1. Restart service ```service mysql-server restart```

Sol2. Please visit: http://www.cnblogs.com/super-lucky/p/superlucky.html
