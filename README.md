# LifeStyle

How to use this project?

Simply clone this project. Then you should have a software with Apache and MySQL support. We have used Xampp in this case.

<b>Steps to create a table using Database</b>

1. Open Shell in Xampp
2. Use "mysql -u root" 
3. Use "create DATABASE id2538044_store;" to create a database of name id2538044_store.
4. CREATE USER 'id2538044_ankur'@'localhost' IDENTIFIED BY '******'; 
  where id2538044_ankur is username and ****** is password.
5. Open the database and run "source C:/xampp/htdocs/mydemo/store.sql";
6. Use command GRANT ALL PRIVILEGES ON id2538044_store.items TO 'id2538044_ankur'@'localhost';
7. Use command GRANT ALL PRIVILEGES ON id2538044_store.users TO 'id2538044_ankur'@'localhost';
8. Use command GRANT ALL PRIVILEGES ON id2538044_store.users_items TO 'id2538044_ankur'@'localhost';
