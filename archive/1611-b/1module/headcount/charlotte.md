Assessed By: Mike

Repo: https://github.com/CjMoore/headcount

Notes:
* 71 tests, 89 assertions, all passing
* 5 Violations of sanitation
* 1 failure of spec harness
* generally well written, some opportunities for refactoring
* I like how File IO was pulled out 
* Look into sad path testing and predicate methods

## Evaluation Rubric

The project will be assessed with the following guidelines:

### 1. Functional Expectations
* 3: Application fulfills expectations of Iterations 0 - 4 *as well as* one of Iterations 5 or 6

### 2. Test-Driven Development

* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality

### 3. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 5. Enumerable & Collections

* 3: Application demonstrates comfortable use of appropriate Enumerable methods

### 6. Code Sanitation

The output from `rake sanitation:all` shows...


* 3: Five or fewer complaints
