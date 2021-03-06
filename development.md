## Building ##

To build and install into the local Maven repository:

`mvn install`

To run the integration tests:

`mvn verify -PrunITs`

You can run integration tests individually via your IDE by running the `uk.co.blackpepper.bowman.test.server.Application` Spring Boot application from the `test/server` module, then running tests using your IDE's JUnit runner. 

## IDE Setup ##

A Checkstyle plugin for your IDE is recommended.

## Code Style Configuration Files ##

Using these code style files for your IDE will help your contribution conform with our Checkstyle rules:

* [Eclipse](https://github.com/BlackPepperSoftware/bp-build/tree/master/src/main/config/eclipse)
* [IDEA](https://github.com/BlackPepperSoftware/bp-build/tree/master/src/main/config/idea/codestyles)
