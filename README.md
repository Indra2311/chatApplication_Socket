# chatApplication_Socket
Installation
$ pip install pymysql
To get these codes run on your local machine
setup Mysql database on your local machine
Fill your info in this line db = pymysql.connect("host","user","pass","db") on your chat_server.py
create "history" table on Mysql use this command create table history (message VARCHAR(100));
