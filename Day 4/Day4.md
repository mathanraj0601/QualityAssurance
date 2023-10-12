# Day - 3

## Functional and non-functional testing

- functional : testing the feature example : login
- non-functional : testing the performance : how many people login at a time, how many second it need after login to enter dashboard

## testing techinque
- There are testing pattern to design test case 

### Boundary value analysis

- While we are testing to reduct test case and make a effective testing we can take boundary values and their max and min.
example : instead of 1 to 10 we cab take 0,1,2 and 9,10,11

### Equivalence Class Partitioning

- In this pattern we split the test case into small partition and take a value in each partition and test.
example;  1-50  to 1-10 and 11 -20 goes on we can take 3,12,eoc

### Decision Table based 

- we can list all possible combination and test
- example : validating all input will enable submit button 

### state transition

- having limited setof values as input
- login first 2 time wrongly will cause incorrect and login failed 3 times cause account block

### Error guessing

- based on work experience with similar application we can predict some error that code may have
