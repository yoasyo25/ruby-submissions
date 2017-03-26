## Evaluation Rubric

Name: Yohanan

Assessor: Lauren

Notes: 

* Again, great psuedocode. 
* Would have loved to see more than one commit so I could follow your thought process - I'd start practicing committing more frequently
* LOVE seeing your unit tests - excellent work there
* Also great use of edge case testing!
* Your source code is wonderfully modular - I would think this is a byproduct of both solid psuedocode and disciplined testing
* I would be careful with hardcoding the index of the check digit in your `exclude_check_digit` method. If you know the check digit is always the last number, you can always get that index with `original_number.length - 1` or something along those lines.
* Excellent effort overall - one thing to start thinking of with your refactors now is how to not daisy-chain your methods. How can you design your class so its methods know little to nothing about other methods?

The project will be assessed with the following guidelines:

### 1. Fundamental Ruby & Style

* **4:  Application demonstrates excellent knowledge of Ruby syntax, style, and refactoring**
* 3:  Application shows strong effort towards organization, content, and refactoring
* 2:  Application runs but the code has long methods, unnecessary or poorly named variables, and needs significant refactoring
* 1:  Application generates syntax error or crashes during execution

### 2. Encapsulation / Breaking Logic into Components

* **4: Application is expertly divided into logical components each with a clear, single responsibility**
* 3: Application effectively breaks logical components apart but breaks the principle of SRP
* 2: Application shows some effort to break logic into components, but the divisions are inconsistent or unclear
* 1: Application logic shows poor decomposition with too much logic mashed together

### 3. Functional Expectations

* 4: Application meets all requirements, and implements one extension properly.
* **3: Application meets all requirements as laid out per the specification.**
* 2: Application runs, but does not work properly, or does not meet specifications.
* 1: Application does not run, crashes on start.
