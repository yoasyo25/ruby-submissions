## Evaluation Rubric

Assessor: Mike

* Application does not run.
* Why are there so many attr_accessors and attr_readers? Do any of the
instance variables here ever accessed outside of the class?
* Think about what about this class is an attribute and should be stored
in an instance variable and should be persisted, and what should not be persisted.
* The problems you are having seem to stem from the fact that you have a lot
of methods which are all modifying these instance variables. Think about how
you would send this data back and forth instead of having them modify the same things.


The project will be assessed with the following guidelines:

### 1. Fundamental Ruby & Style

* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring

### 2. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 3. Functional Expectations

* 1: Application does not run, crashes on start.
