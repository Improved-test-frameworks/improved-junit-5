![status](https://badgen.net/static/status/planned/grey/)

# Improved JUnit 5

This project contains a test framework that improves on JUnit 5's default functionality.

## Requirements

### Mocking

- The framework must be able to automatically mock away everything in the system under test.
- Variables in the class to be tested can be excluded or included to the automatic mocking using annotations or the super() call.
- The automatic mocking must also work for static variables, methods and classes.

### Auto print

- The framework must have auto prints which add display names and console prints based on the test function name.
- The auto print feature must be able to be customized to exclude certain words from the function name.
- The auto print feature must be able to be customized to add, remove or alter keywords.
- The auto print feature must be able to be customized to change the color of the console output.

### Log files

- The framework must be able to write test log files to read back test executions.
- The test log files must be able to be grouped in success, fail and error files.
- The amount of test execution results to save must be able to be customized.
- The tests to log must be able to be customized.

### Easy tests

- The framework must have easy tests where a tester can add new tests using one line of code.
- The easy tests must work with multiple parameters.
- The easy tests must work for classes, records and methods.

### Other

- The framework must be able to be installed as a Maven dependency.
