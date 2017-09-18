# Word Watch Submission

* Developer: Bao
* Evaluated by: Casey

## Repo

* https://github.com/rongxanh88/word_watch

## Self Assessment Rubric

*Of "Above", "Meets", and "Below" expectations, describe why you deserve which one.*

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

Above Expectations

* Meets Expectations - I completed all of the user stories.

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

* Meets Expectations - I have DOM manipulation all in one file (view-helper), talk to the API solely through the Word model class, and I have events all in the events.js file.

Below Expectations

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

Above Expectations

* Meets Expectations - events.js file is required within the document.ready function. I target the CSS by targeting the parent's class name and the child's HTML tag.

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

* Meets Expectations - use ES6 syntax, using only `const` or `let`. I use arrow functions everywhere since I did not need `this` binded to anything. I did not use semicolons, and I camelCased my variables.

Below Expectations

## Evaluation Rubric

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

**Above Expectations** - The developer completed all the stories present.

Meets Expectations

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

**Meets Expectations** - I think you could take this a step further and follow the MVC pattern or another design pattern even, but this is a great start - you definitely meet expectations on this one. You have a solid code quality.

Below Expectations

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

Above Expectations

**Meets Expectations** - There are a few times you need to call `[0]` to get the correct element - this is dependent on the order of elements on the page which could potentially be fragile. I encourage you to always be as specific as possible!

Below Expectations

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

**Above Expectations** - You followed all JS conventions - great job!

Meets Expectations

Below Expectations
