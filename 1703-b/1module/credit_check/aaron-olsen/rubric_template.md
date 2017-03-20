## Evaluation Rubric

Name:

Assessor: Mike

* Watch your whitespace, there should not be padding in method definitions.
* I would rather see you avoid the use of ternaries, except in the case of
extremely simple conditionals.
* On line 26, relatively complex operations should always take place on
multiple lines - this increases readability.
* Generally you don't want to modify a collection as you did with the use of
`map!` Better to create a new collection.
* Luhn check method does a bit too much, perhaps break things out a bit more.
Good rule of thumb to determine when to break out code to multiple methods is
describe it out loud what it does in English - it feels like youre saying
`and` way too many times, you probably are doing too much in it.
* Look into the shorthand for using reduce to grab a sum.
* Overall, good implementation, but think a lot about what you can do to
increase simplicity and readability.


The project will be assessed with the following guidelines:

### 1. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 2. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 3. Functional Expectations

* 3: Application meets all requirements as laid out per the specification.
