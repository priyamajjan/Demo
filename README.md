This example demonstrates how to collect code coverage by integration tests, tests are located in a separate Java Maven module.
SonarQube aggregates code coverage by unit tests and integration tests to compute an overall code coverage.



Prerequisites
=============
* [SonarQube](http://www.sonarqube.org/downloads/) 
* Maven 3+ 
hi hello hey
1233
Usage
=====
* Build the project, execute all the tests and analyze the project with SonarQube Scanner for Maven:

        mvn clean install sonar:sonar
