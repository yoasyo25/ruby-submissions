## Evaluation Rubric

Name: Mason

Assessor: Lauren

Notes:

* Solid, dynamic solution for validating numbers of any length
* `for .. in` is not a common Ruby practice, although it works. It's more common to use an enumerable such as `each` to run a loop like that
* For future programs, I'd push yourself to break out your logic into methods, ideally, each with their own single responsibility (SRP == Single Responsibility Principle)
* Once you're working in that direction, I'd then aim to structure your programs to be class-based (i.e., create a `CreditCheck` class that is initialized with a cc number, then validated.)
* That being said, you have a solid solution. This iteration helps make refactoring into method- and class-based solutions much less troublesome.

The project will be assessed with the following guidelines:

### 1. Fundamental Ruby & Style

* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
* 3:  Application shows strong effort towards organization, content, and refactoring
* **2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring**
* 1:  Application generates syntax error or crashes during execution

### 2. Encapsulation / Breaking Logic into Components

* 4: Application is expertly divided into logical components each with a clear, single responsibility
* 3: Application effectively breaks logical components apart but breaks the principle of SRP
* 2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear
* **1: Application logic shows poor decomposition with too much logic mashed together**

### 3. Functional Expectations

* **4: Application meets all requirements, and implements one extension properly.**
* 3: Application meets all requirements as laid out per the specification.
* 2: Application runs, but does not work properly, or does not meet specifications.
* 1: Application does not run, crashes on start.
