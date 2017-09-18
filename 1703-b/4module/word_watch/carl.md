# Word Watch Submission

Developer: Carl
Evaluated by:

## Repo

[repo](https://github.com/ACC25/word_watch)

## Self Assessment Rubric

*Of "Above", "Meets", and "Below" expectations, describe why you deserve which one.*

### 1. Completion:

+ Touched on every user story.
**Meets Expectations**

### 2. Code quality
  * Developer breaks functions out into separate responsibilities for:
    * DOM manipulation
    * API interactions
    * data processing
  * Developer has no functions that exceed 8 lines.
  * Developer uses `Array.prototype` functions over `for` loops where appropriate.
  * Developer deals with async API requests in a readable, coherent way.

+ I think I met the expectations of the test, breaking out responsibility for API and data manipulations, although I could have broken it down further and seperated dom manipulation into it's own class. 
+ I think I wrote the API requests in a readable, coherent way.
+ I think I could have followed OOP principles more closely, as I do not pass around classes (in the ruby sense). My aim was to meet the functional expectations of the assignment first and refactor later and I think I could refactor this code to be very clean with time. 
**Meets Expectations**


### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

+ I think I contained all my event listeners within `document.ready` and didn't used more than 2 css selectors at a time.
**Meets Expectations**

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

+ I think I followed JS convention for the most part and was consistent in not using semicolons.
+ I believe I have some mix of Jquery and raw JS, which could be refactored to be more consistent.
**Meets Expectations**


## Instructor Rubric

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

Above Expectations

**Meets Expectations** - All challenges complete (the top word functionality was a little broken due to pointing to localhost rather than the hosted API).

Below Expectations

### 2. Code quality
  * Developer breaks functions out into separate responsibilities for:
    * DOM manipulation
    * API interactions
    * data processing
  * Developer has no functions that exceed 8 lines.
  * Developer uses `Array.prototype` functions over `for` loops where appropriate.
  * Developer deals with async API requests in a readable, coherent way.

Above Expectations

**Meets Expectations** - You separated responsibility as best you code in the given time. There's room for improvement and room to further break things down - you could even follow the MVC design pattern as a way of organizing your code. No functions are too long and your code is readable and variables are well-named.

Below Expectations

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

Above Expectations

**Meets Expectations** - You don't traverse the DOM through parents and children - you register events in a way that makes sense and is easy to read.

Below Expectations

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

Above Expectations

**Meets Expectations** - You follow JS conventions well - good job!

Below Expectations
