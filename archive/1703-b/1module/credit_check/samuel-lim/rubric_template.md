## Evaluation Rubric

Name: Sam

Assessor: Lauren

Things to note:
* Careful with convention - your method `isValid?` should just be `valid?` (or at least using snake_case: `is_valid?`)
* great job using a `CardChecker` class for this, love seeing efforts towards class-based solutions

Future refactors worth making:
* Aim for smaller methods with only a single responsibility. For example, many lines of logic within your `check_card` method could be extracted out into their own methods
* With something like line 24 (`card_number_times_two.each do |i|`), and pushing results into your `final` array, try thinking through a different enumerable that could return a new array for you (`.map`), thus eliminating the need to explicitly push results into a new array

Overall, strong start, would love to see you push further on the next project.

The project will be assessed with the following guidelines:

### 1. Fundamental Ruby & Style

* 4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring
* 3:  Application shows strong effort towards organization, content, and refactoring
* **2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring**
* 1:  Application generates syntax error or crashes during execution

### 2. Encapsulation / Breaking Logic into Components

* 4: Application is expertly divided into logical components each with a clear, single responsibility
* 3: Application effectively breaks logical components apart but breaks the principle of SRP
* **2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear**
* 1: Application logic shows poor decomposition with too much logic mashed together

### 3. Functional Expectations

* **4: Application meets all requirements, and implements one extension properly.**
* 3: Application meets all requirements as laid out per the specification.
* 2: Application runs, but does not work properly, or does not meet specifications.
* 1: Application does not run, crashes on start.
