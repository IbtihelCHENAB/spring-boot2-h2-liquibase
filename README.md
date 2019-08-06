# spring-boot2-h2-liquibase

A simple project to demostrate how to setup spring boot liquibase using the in-memory database H2.

### How it works

clone the codebase 

```
git clone https://github.com/IbtihelCHENAB/spring-boot2-h2-liquibase.git
```
compile & package

```
mvn clean package
````
And then run 

```
mvn spring-boot:run
```

Go to http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:testdb
User Name: sa
Password: Leave it blank

Now you have access to the in-memory H2 database dashboard in which you will find all the changes that you made using liquibase configuration.
