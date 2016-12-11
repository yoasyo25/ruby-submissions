Assessed By: Beth Sebian

Repo: https://github.com/drod1000/black_thursday

Notes:
* Beautiful testing suite, nice balance of integration and unit testing
* Went a little overboard on assertions; only need one to target claim, split into separate tests if targeting different cases
* Consistent implementation of best-choice enumerables
* Complete through i4
* 0 rake sanitation errors
* Use of one module (SAAssistant) and Merchant Assistant class to delegate functionality and uphold SRP

Scores:

### 1. Functional Expectations
* 3: Application implements iterations 0, 1, 2, 3, and either 4 or 5

### 2. Test-Driven Development
* 4: Application is broken into components which are well tested in both isolation and integration using appropriate data

### 3. Encapsulation / Breaking Logic into Components
* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 4. Fundamental Ruby & Style
* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring

### 5. Enumerable & Collections
* 4: Application consistently makes use of the best-choice Enumerable methods

### 6. Code Sanitation
The output from `rake sanitation:all` shows...
* 4: Zero complaints
