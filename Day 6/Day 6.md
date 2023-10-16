# Day - 6

## Test scenerio 

- It is used to check the functionality of the application from the end-user point of view.

## Scenerio testing

- It is creating scenerio that align with real world to test an application end to end from user prespective than using a test case

## When to use and when not to use scenerio testing.

when to :
- It is very useful in testing most important part of the application to make sure it will work in almost all real world case scenerio.
- By verfying with the stack holder we can assure how application should perform in that scenerio.

when not to use :
- when the application is unstable, not working properly and in case of regression testing
> Regression testing is testing the new change made to the existing project and ensure it work well

## Creation of scenerio
- Read requirements -> think from user POV -> determine scenerio -> trace matrix to check every requirement are covered -> reviewed by stack holder

> Tips : A single scenerio for each user story. if scenerio can text mutliple functionality(requirement) make sure it test individual requirement with some other scenerio.

example : login, search opertion etc.,

[Reference for test scenerio](https://www.guru99.com/test-scenario.html)


## Test case 

- It is a action executed to test feature of an application

> Test scenerio is vague / wide and test case are more specific
example : login as a scenerio there are lot of possibility like email validation etc., they are test case

## Test case table

|test Id|Test case description|Test data|expected result|Pass/fail|
|:---:|:---:|:---:|:---:|:---:|

Decription: explain testcase
test data : sample data to test
Expected result : what is the result of it
pass /fail : to analyze outcome

> Note: There may be field in the table to give requirement like  browser should be firefox (pre-condition)

## Test case best pratice

- simlpe, keep user in mind, avoid repitition (reference the reapting test case from here), Do not assume , 100% covergae,identifiable (test_id),use pattern learned in day 4 , self-cleaning (after execution test environment should be return back to original state), Repeatable (any one can run the test and get the sample response),peer review for test cases.

> Use test management tool for creating and monitoring test cases. like jira and quality center.

[Reference for test case](https://www.guru99.com/test-case.html) : s*link has a sample test case excel template*
