## Assessor: Lauren

## Repo: https://github.com/baileyward/night_writer-

## Notes:

* 80 character rule cuts off text vs wraps.
* All files should have code contained by classes.
* Longer methods could/should be broken into smaller methods.
* NightWriter should be broken into an additional separate NightReader class.
  * encode_from_braille would then be broken into multiple methods in NightReader
* TDD was weak/backfilled - NightWriter's over-encapsulation shows as a result.

## Evaluation Rubric

The project will be assessed with the following rubric:

### 1. Fundamental Ruby & Style

* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
* **3:  Application shows strong effort towards organization, content, and refactoring**
* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring
* 1:  Application generates syntax error or crashes during execution

### 2. Test-Driven Development

* 4: Application is broken into components which are well tested in both isolation and integration using appropriate data
* 3: Application is well tested but does not balance isolation and integration tests, using only the data necessary to test the functionality
* **2: Application makes some use of tests, but the coverage is insufficient**
* 1: Application does not demonstrate strong use of TDD

### 3. Encapsulation / Breaking Logic into Components

* 4: Application always breaks concepts into classes and methods which encapsulate functionality.
* 3: Application consistently breaks concepts into classes and methods which have appropriate scope and responsibilities (SRP).
* **2: Application makes use of some classes, but the divisions or encapsulation are unclear.**
* 1: Application makes use of just a few huge methods to control the bulk of the functionality.

### 4. Functional Expectations

* 4: Application meets all requirements, and implements one extension properly.
* **3: Application meets all requirements as laid out per the specification.**
* 2: Application runs, but does not work properly, or does not meet specifications.
* 1: Application does not run, crashes on start.
