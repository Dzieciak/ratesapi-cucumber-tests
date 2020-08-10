# ratesapi-cucumber-tests

This is a demo project for testing [ratesapi.io](http://ratesapi.io). It is based on Cucumber JVM and Spring.

## Running tests

Run the following command inside project main directory to execute all tests:

`mvn clean verify -Pcucumber-test -Dcucumber.filter.tags="@Ratesapi" -Dthread.count=4`

Please refer to Cucumber documentation for explanation, how to use 'cucumber.filter.tags' parameter.
Parameter `thread.count` can be used to specify number of threads for executing scenarios.

## Reports

Test reports can be found under `target/cucumber` directory. There are two reports:
* HTML report - open `target/cucumber/cucumber-html-reports/overview-features.html` for the report main page
* timeline report - open `target/cucumber/timeline/index.html` for the report main page
