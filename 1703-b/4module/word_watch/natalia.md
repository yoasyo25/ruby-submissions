# Word Watch Submission

Developer: Natalia

Evaluated by: Schutte

## Repo

* [NataliaColome_WordWatch](https://github.com/nmcolome/word_watch)

## Self Assessment Rubric

*Of "Above", "Meets", and "Below" expectations, describe why you deserve which one.*

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

**Above Expectations** I did them all

### 2. Code quality
  * Developer breaks functions out into separate responsibilities for:
    * DOM manipulation
    * API interactions
    * data processing
  * Developer has no functions that exceed 8 lines.
  * Developer uses `Array.prototype` functions over `for` loops where appropriate.
  * Developer deals with async API requests in a readable, coherent way.

**Above Expectations** I respect SRP, I have separate functions for DOM manipulation, API, appending to html, etc. None of my functions exceed 8 lines. I used map and reduce when appropriate, used for loops when I didn't want to return an array and I chose for loops instead of forEach because it is faster.

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

**Above Expectations** It is within document.ready and I added classes to avoid traversing children.

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

**Above Expectations** I did all of them and even used classes. The only es6 style I didn't use was fat arrows because I used a reduce and didn't know how the syntax would change; so to avoid problems (time constraint) I didn't use them.

## Rubric

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

**Above Expectations**

### 2. Code quality
  * Developer breaks functions out into separate responsibilities for:
    * DOM manipulation
    * API interactions
    * data processing
  * Developer has no functions that exceed 8 lines.
  * Developer uses `Array.prototype` functions over `for` loops where appropriate.
  * Developer deals with async API requests in a readable, coherent way.

**Meets Expectations**

You already do a great job hiding implementation details from the document ready listener, so this bit: https://github.com/nmcolome/word_watch/blob/master/src/index.js#L8-L12 is inconsistent.

For "Above", we'd like to see things like separating out different scopes of
functionality. E.g., an API service class, and DOM manipulation class, etc.

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

**Meets Expectations**

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

**Meets Expectations**

Great job! You wrote very clean code 👍

