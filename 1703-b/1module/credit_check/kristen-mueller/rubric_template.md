## Evaluation Rubric

Name: Squee

Assessor: Lauren

Notes:

* Dynamic, modular solution - made reaching that extension a breeze!
* Great work building modular methods with (mostly) single responsibilities
  * There is some logic that could be further extracted into separate methods, though
  * For example, within your `multiply_by_two` method, `split_long_number(cc_number).reverse` could actually be its own method, responsible for reversing the split number
* Another refactor to start aiming for is not daisy chaining your methods as much, and designing your program's methods to know less about each other. We'll start looking into strategies for this together in class soon.
* Lastly, would love to start seeing you push towards using classes throughout your programs - again, we'll be pushing this practice more soon.

The project will be assessed with the following guidelines:

### 1. Fundamental Ruby & Style

* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
* **3:  Application shows strong effort towards organization, content, and refactoring**
* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring
* 1:  Application generates syntax error or crashes during execution

### 2. Encapsulation / Breaking Logic into Components

* 4: Application is expertly divided into logical components each with a clear, single responsibility
* **3: Application effectively breaks logical components apart but breaks the principle of SRP**
* 2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear
* 1: Application logic shows poor decomposition with too much logic mashed together

### 3. Functional Expectations

* **4: Application meets all requirements, and implements one extension properly.**
* 3: Application meets all requirements as laid out per the specification.
* 2: Application runs, but does not work properly, or does not meet specifications.
* 1: Application does not run, crashes on start.
