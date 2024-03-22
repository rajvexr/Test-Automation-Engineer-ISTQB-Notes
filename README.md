# Test-Automation-Engineer-ISTQB-Notes


## Section 1: Introduction to Test Automation

Test automation is expected to help run many test cases consistency and repeatedly on different versions of the SUT and/or enviroments. But test automation is more than a mechanism for running a test suit without human interaction. 

### Test automation involves a process of designing the testware, including:

- Software
- Documentation
- Test Cases
- Test Enviroments 
- Test Data


### Testware is necessary for the testing activities that include:

- Implementing automated test cases 
- Monitoring and controlling the execution of automated tests
- Interpreting, reporting and logging the automated test results


### Test automation has different approaches for interacting with a SUT (System Under Test):

- API/Web Services: Testing through the public interfaces to classes, modules or lkibraries of the SUT (API Testing)
- User interface: Testing through the user interface of the SUT (e.g. GUI testing or CLI testing)
- Service/Protocol: Testing through the a service or protocol

### Objectives/Goal of test automation include:

- improving the test efficency
- Providing wider function coverage
- Reducing the total test cost
- Perfoming test that manual tester cannot
- Shortening the test execution period
- Increasing the test frequency/reducing the time required for test cycles


### Advantages of test automation include:

- More tests can be run per build (takes less time for automation to run tests)
- The possibility to create tests cannot be done manually (real-time, remote and parallel tests)
- Tests can be more complex (doing it manually can be complicated)
- Tests run faster 
- Tests are less subject to operator error
- More effective and efficent use of testing resources
- Quicker feedback regarding software quality
- Improved system reliability (repeatability, consistency, not prone to human error)
- Improved consistency of tests (Same results everytime)

### Disadvantages of test automation include:

- Additional costs are involved
- Inital investment to setup TAS
- Requires additional technologies
- Team needs to have development and automation skills
- On-going TAS maintance requirement
- Can distract from testing objectives (focusing on automatinmg tests casews at the expense of executing tests)
- Tests can become more complex
- Additional error may be introduces by automation

### Limitations of test automation include:

- Not all manual test cases can be automated
- The automation can only check machine-interpretable results
- The automation can only check results that can be verified by an automated test oracle
- Not a replacement for exploratory testing 

### Major success factors for test automation include the following:

### Test Automation Architecture (TAA)

- The Test Automation Architecture (TAA) is very closely aligned with the architecture of a software product. It should be clear which functional and non-functional requirements the architecture is to support. Typically this will be the most important requirements.
- Often TAA is designed for maintainability, performance and learnability. It is helpful to involve software engineers who understand the architecture of the SUT.

### SUT Testability

- The SUT needs to be designed for testability that supports automated testing. In the case of GUI testing, this could mean that the SUT should decouple as much as possible the GUI interaction and data from the appearance of the graphical interface. 
- In the case of API testing, this could mean that more classes, modules or the command-line interface need to be exposed as public so that they can be tested.
- The testable parts of the SUT should be targeted first. Generally, a key factor in the success of test automation lies in the ease of implementing automated test scripts.

### Test Automation Strategy
- A practical and consistent test automation strategy that addresses maintainability and consistency of the SUT.
- It may not be possible to apply the test automation strategy in the same way to both old and new parts of the SUT. When creating the automation strategy, consider the costs, benefits and risks of applying it to different parts of the code.
- Consideration should be given to testing both the user interface and the API with automated test cases to check the consistency of the results 

### Test Automation Framework (TAF)
A test automation framework (TAF) that is easy to use, well documented and maintainable, supports a consistent approach to automating tests.

In order to establish an easy to use and maintainable TAF, the following must be done: 

- Implement reporting facilities
- Enable easy troubleshooting
- Address the test enviroment appropriatley
- Document the automated test cases
-  Trace the automated tests
-  Enable easy maintance
-  Keep the automated tests up to date
-  Plan for development
-  Retire tests as needed
-  Monitor and restore the SUT






