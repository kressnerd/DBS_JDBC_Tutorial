# DBS_JDBC_Tutorial

This is a Java file for the database course to demonstrate JDBC. It contains very bad spaghetti code just for a quick and dirty demonstration!

Get a PostgreSQL up and running:
https://wiki.postgresql.org/wiki/PostgreSQL_For_Development_With_Vagrant

Do the first two chapters of the PostgreSQL tutorial:
http://www.postgresql.org/docs/9.4/static/tutorial.html

Now you have the database schema and the data that is used in the JDBC test class.

Download the JDBC driver and add the jar to the CLASSPATH, e.g.
https://jdbc.postgresql.org
```shell
export CLASSPATH = $CLASSPATH:./postgresql-9.4-1201.jdbc41.jar
```

Compile and run the JDBC test class
```shell
javac src/de/fu_berlin/mi/ag_db/dbs/tutjdbc/DBSConTest.java
```
