# Day - 7

## Test environment setup 

- The process of configuring hardware and software to run the testcase and testdata to test the application. It is very important to make the testing sucesss

- The setup is done by developer,tester, sys admins

## Test environmen requirement

- set up server (for frontend,backend,database)
- config network, internet so that congestion due to this will not affect anyone
- set up PC with different os and browser to test the application
- Bug reporting tool like project management tool
- creating test data by tester or copy from prodution data 
  - production data invloves some sensitive info so there are two ways for that
    - black list : leave user entered data
    - white list : take only allowed field to copy


## Test checklist

- software
- hardware
- data
- management tools

## Challenging

- Remote connection
- usage by different team
- ineffective planning for intergration testing.
- complex test config

## Test bed 

- It is software testing environment for more specific activities like developer want to test a application for certain feature like in a production environment.

[Reference for test environment](https://www.guru99.com/test-environment-software-testing.html)


## Test Execution

- It is the process of running the test case in order to ensure the application functioning correctly, meet requirements.

## Activities of test execution

- Finding defect and reporting to dev team to work.
- After Dev fixed the bug map again the test case to ensure the test case.
- Re test the application to ensure the application work fine
- Regression testing to test the new changes without affecting existing application.
- System intergraion test to check application as a whole in single run

## Phase of test execution

- Creation of test case
- Execution of test case
- Validation of test case

## Test execution priorties

- It is based on complexity, risk convered, depth (specfic functionality in module), breadth (entire module), platform.

## Test execution states

- pass : successfull
- fail : not sucessfull
- not run 
- partially executed : few test case not run
- inconclusive : though sucess require more analysis
- In progress : currently running
- un expected result : success but result are un expected.

> Test execution process is similar to STLC

## Test Report

- It is report consist of info like who write,execute testcase,no of test case executed and remaining etc.,

[Reference for test execution](https://www.geeksforgeeks.org/test-execution-for-software-testing/)

##  Test closure 

- It is the document / report which has all the details regarding the test that is taken place during the Software development

## Need for test closure
- It help stackholder to analyse the quality of the application
- to announce end of testing
- Metric to give client about the error history
- It enable customer to understand the strength and weekness.