Assessed By:
Ali  

Repo:

Notes:
Through Iter 3
Testing:
109 tests & assertions  
80% coverage
Used based data, some fixtures for more isolated functionality i.e. merchant
Testing off MerchantRepo for the Merchant test
Ruby Style:  
Variable names do not illustrate what they are holding (i.e. a, x)
Talked about how to break long method chains into methods on related classes
find, find_all, map, each
Convert row to hash, then hash to Merchant info
Many methods that use multiple enumerables
Reaching through multiple classes to run methods  


### 1. Fundamental Ruby & Style

*   2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring

### 2. Breaking Logic into Components

*   3: Application effectively breaks logical components apart but breaks the principle of SRP

### 3. Test-Driven Development

*   3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 4. Functional Expectations

*   2: Application implements iterations 0, 1, 2, and 3

### 5. Code Sanitation

The output from `rake sanitation:all` shows...

*   4: Zero complaints
