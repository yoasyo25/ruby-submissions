## Evaluation Rubric

Assessor: Mike

* I would probably just use a conditional with two statements for the puts_valid
method.
* Some of your methods are doing a bit too much - chaining methods is fine,
some of yours go a little too far. A good way to tell this is to describe
what each method does out loud - if you use the word "and" too many times,
functionality should probably be broken out.
* Default to using the multi-line syntax over single line, it helps with
decomposition and readability. Same reason to avoid using ternary statements.
* In one of your methods you are using an enumerable to shovel code into
an outside of the enumerable. Is there a way to set this up that youre not
using any extraneous variables?

The project will be assessed with the following guidelines:

### 1. Fundamental Ruby & Style

* 3:  Application shows strong effort towards organization, content, and refactoring

### 2. Encapsulation / Breaking Logic into Components

* 3: Application effectively breaks logical components apart but breaks the principle of SRP

### 3. Functional Expectations

* 3: Application meets all requirements as laid out per the specification.
