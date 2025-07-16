#inside frontend-app directory
docker build -t frontend-app . 

# inside flask directory
docker build -t flask-app . 


 # in root directory 

docker-compose up --build

# After this


C:\Users\1by22\OneDrive\Desktop\New folder>docker exec -it newfolder-db-1 mysql -u root -p
Enter password:

Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 5
Server version: 5.7.44 MySQL Community Server (GPL)

Copyright (c) 2000, 2023, Oracle and/or its affiliates.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql> show databases;
+--------------------+
| Database           |
+--------------------+
| information_schema |
| mysql              |
| performance_schema |
| sampledb           |
| sys                |
+--------------------+
5 rows in set (0.00 sec)

mysql>
