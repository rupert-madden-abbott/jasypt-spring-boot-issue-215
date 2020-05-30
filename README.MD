# jasypt-spring-boot-issue-215

This repository attempts to replicate [jasypt-spring-boot issue 215](https://github.com/ulisesbocchio/jasypt-spring-boot/issues/215).

Run:

```
mvn clean package
java -Djasypt.encryptor.password=password -jar target/app.jar
```