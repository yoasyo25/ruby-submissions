## Evaluation Rubric

Name: Nick

Assessor: Lauren

Notes:

* LOVE the design of this solution (class-based, one public runner method, private methods only meant to be used by the instance of the class). Keep on that track
* Stylistically, no need to explicitly state `return` in Ruby. The last line of a method will always be a method's implicit return value, thus it's most in convention to rely on that.
* Another refactor to consider:  rather than using `each` and shoveling things into a new array from its block, try out different enumberables, such as `map` that will return a new array for you based on whatever logic you execute within its block.
* **NOTE** Somewhere within your code, your logic is incorrect. I've checked against multiple valid and invalid numbers, and am getting inconsistent results. I'm happy to help you troubleshoot with you if it's unclear where that's happening.

The project will be assessed with the following guidelines:

### 1. Fundamental Ruby & Style

* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
* **3:  Application shows strong effort towards organization, content, and refactoring**
* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring
* 1:  Application generates syntax error or crashes during execution

### 2. Encapsulation / Breaking Logic into Components

* **4: Application is expertly divided into logical components each with a clear, single responsibility**
* 3: Application effectively breaks logical components apart but breaks the principle of SRP
* 2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear
* 1: Application logic shows poor decomposition with too much logic mashed together

### 3. Functional Expectations

* 4: Application meets all requirements, and implements one extension properly.
* 3: Application meets all requirements as laid out per the specification.
* **2: Application runs, but does not work properly, or does not meet specifications.**
* 1: Application does not run, crashes on start.
