splitmysql
==========
This repo is used to extract some of the tables from a mysqldump file.

#For example
You have a mysqldump file named "livedata.sql" and you need to extract a table called "stock".

  ```
user@machine:~ sh splitmysql.sh livedata.sql stock

  ```
This will extract the stock table in the present directory. 
