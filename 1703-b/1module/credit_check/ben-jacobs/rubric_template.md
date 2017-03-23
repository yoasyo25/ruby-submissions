## Evaluation Rubric

Assessor: Mike

* Glad you used a class.
* The code is decomposed into separate methods well.
* Do you need things to be an attr_accessor? Do we ever need to set the value
of instance variables from outside of the class?
* The three items you are storing as instance variables, are they attributes
of the class? Should they be stored as instance variables, which are
expensive, or should the information they contain be passed around as messages
from one method to another?
* Look into converting strings into an array with characters and then
iterating over that as opposed to using a for loop. It's much easier and you
have to reinvent fewer wheels using prebuilt enumerables.


The project will be assessed with the following guidelines:

### 1. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 2. Encapsulation / Breaking Logic into Components

* 4: Application is expertly divided into logical components each with a clear, single responsibility

### 3. Functional Expectations

* 4: Application meets all requirements, and implements one extension properly.
