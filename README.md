# API Test Automation Framework
This project demonstrates how pytest can be put together to create an API automation tool to assist in regression testing.

### Multivation for putting together an API testing framework

##### when testing apis I usually found myself repeating alot test code and I knew this is wrong. I strongly believe that api tests should be:
    - Test data driven - scenarios should drive tests.
    - There should be minimal repetition on test code. DRY Principal
    - Stand alone - tests should not depend on each other, or else there should be minimal dependancy.
    - Test dependancy comes in handy when testing business logic.
    - Any part of API under test should be configurable, i.e remove any hard coding as much as possible.

###### Therefore there is a need to organize test process or flow to ensure that apis tests yield maximum benefits like test accuracy,maintainance and speed.

### **Organization of api framework: process**

  1. setup code(code executed before any test is run).
  2. session management - managing session objects and data.
  3. Test data generation - important for concurrent tests.
  4. parametrizing tests - since the framework is test data driven and need to run tests concurrently.
  5. writting a conftest file e.g fixtures and extra commandline arguments
  6. collecting tests
  7. marking tests - helps to choose which tests to execute.
  8. running tests - concurrent execution of tests for speed.
  9. test reporting - allure, html, and json reports

### prerequisite
  - [python 3](https://www.python.org/downloads/) should be installed

### Installation
```pip install pytest``` - **installs the most recent version**


### Important links
  - [pytest official documentation](http://pytest.org/en/latest/)
  - [Simple guide to api testing](https://www.softwaretestingclass.com/simple-guide-to-learn-api-testing/)
  
  **to do - add more details**
  
 
