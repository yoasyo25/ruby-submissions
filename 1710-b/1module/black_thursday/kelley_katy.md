* **Evaluator:** Mike
* **Repo:** https://github.com/kelleyjenkins/black_thursday
* **Notes**
* Some opportunities to refactor by pulling out pieces of methods into their
own methods.
* Please don't use #method next time
* Tests all pass
* Did I4, spec harness all passes
* Overall, pretty clean code
* Would like to have seen more use of mocks and stubs in the tests rather than
loading the whole SE in Repositories, etc etc


## Evaluation Rubric

The project will be assessed with the following guidelines:

### 1. Ruby Syntax & Style

Expectations:

- [x] Applies appropriate attribute encapsulation
- [x] Developer creates instance and local variables appropriately
- [x] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable
- [ ] Developer implements best-choice enumerable methods
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line

* 3: Meets expectations

### 2. Breaking Logic into Components

Expectations:

- [x] Code is effectively broken into methods & classes
- [x] Developer writes methods less than 6 lines
- [ ] No more than 3 methods break the principle of SRP

* 3: Meets expectations

### 3. Test-Driven Development

Expectations:

- [ ] Each method is tested
- [x] Functionality is accurately covered
- [x] Tests implement Ruby syntax & style
- [x] Balances unit and integration tests
- [ ] Evidence of edge cases testing
- [x] Test Coverage metrics are present (SimpleCov)
- [x] A test RakeTask is implemented

* 3: Meets expectations

### 4. Functionality

Expectations:

- [x] Application meets all requirements (all relevant tests pass the spec harness)

* 3: Meets expectations

### 5. Version Control

- [x] Developer commits at a pace of at least 1 commit per hour
- [x] Developer implements branching and PRs
- [x] The final submitted version is merged into master

* 3: Meets expectations

### 6. Code Sanitation

- [x] The output from `rake sanitation:all` shows five or fewer complaints

* 4: Above expectations
