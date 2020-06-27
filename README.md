# BlogPost2020
Just Basic of Blog Post
<br><br>
Make database and tables 
<pre>
mysql> CREATE DATABASE flog_db;
Query OK, 1 row affected (0,00 sec)

mysql> USE flog_db;
Database changed
mysql> 
</pre>

<pre>
mysql> CREATE TABLE user(user_id int auto_increment, first_name varchar(20), last_name varchar(20), username varchar(20) unique, email varchar(30) unique, password varchar(100), primary key(user_id));
Query OK, 0 rows affected (0,52 sec)
</pre>

<pre>
mysql> CREATE TABLE blog(blog_id int auto_increment, title varchar(100), author
varchar(40), body mediumtext, primary key(blog_id));
Query OK, 0 rows affected (0,28 sec)
</pre>