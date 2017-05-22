Assessed By: Jeff

Repo:

Notes:

* Have about 35 tests, some with the server and some without
* Test suite is pretty solid with room for more edge cases and experimentation
* Implementation shows a middle-of-the-road "design" that's very well implemented
* Recommend reading up on Metz' POODR to think about stepping up componentization and design of the system
* Ruby syntax, enums, etc show care and attention

Scores:

### 1. Overall Functionality

* 3: Application implements iterations 0 - 4

### 2. Fundamental Ruby & Style

* 3:  Application shows some effort toward organization but still has 6 or fewer long methods (> 8 lines) and needs some refactoring.

### 3. Test-Driven Development

* 3: Application uses tests to exercise core functionality and some edge cases, but fails to break out component objects/tests.

### 4. Breaking Logic into Components

* 2: Application has some logical components but divisions of responsibility are inconsistent or unclear and/or there is a "God" object taking too much responsibility
