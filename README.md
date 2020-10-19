# junit-test
Project to debug maven-surefire with junit5 and junit4 configuration

## Structure of the project
`junit-test` has a multi-module maven project structure with just one module `test-module`. The pom file in junit-test also inherits another pom file from `parent_pom`.


## Steps to reproduce the problem

1. Go to test-module
2. Run `mvn clean install`
3. `com.sample.project.tests.JUnit4Tests` will be run twice.
