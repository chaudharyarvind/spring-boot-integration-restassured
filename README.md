# Spring boot Rest-assured Integration Test
Put integration test seperate to unit test and use failsafe plugin to run integration test.

#To run unit test

````
mvn clean test
````

#To run integration test

```
cd target
mvn integration-test -P integration
```

