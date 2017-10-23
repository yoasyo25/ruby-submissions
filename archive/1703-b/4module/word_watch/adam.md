# Word Watch Submission

Developer: Adam
Evaluated by:

## Repo

* https://github.com/adamgunther1/word_watch

## Self Assessment Rubric

*Of "Above", "Meets", and "Below" expectations, describe why you deserve which one.*

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

**Above Expectations**
Challenges 1-5 were completed with plenty of time and full functionality.

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

**Above Expectations**
DOM manipulation, API calls, and data processing are in single responsibility functions, functions are below 8 lines, enumerables are used instead of for loops. Javascript are organized into Single Responsibility classes

Meets Expectations

Below Expectations

### 3. Events and DOM manipulation
  * Developer registers event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

**Above Expectations**
Solid targeting of nodes and document.ready event listeners.

Meets Expectations

Below Expectations

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

**Above Expectations**
Uses consistent ES6 syntax and proper naminbg conventions

Meets Expectations

Below Expectations

## Instructor Rubric

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

**Above Expectations** - All functionality for challenges 1-5 is present and works as expected.

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

**Meets Expectations** - I think the WordCloud object could be broken down even further. A specific Word doesn't need to know how to append itself to the page or calculate the number of times it appears or even post it to a third party service. I encourage you to try to make connections between how we organize our Ruby code to improve (even further) your JS code quality. I do like that you've broken your functions down and kept them as single responsibility as possible. Also - needing to call `word.word` is confusing!

Below Expectations

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

**Above Expectations** - You did a great job assigning specific event listeners and traversing the DOM in a way that doesn't rely on parents/children. You were as specific as possible when manipulating the DOM.

Meets Expectations

Below Expectations

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

**Above Expectations** - Good job following JS conventions - the one thing I'd suggest is to be mindful about choosing variable names - at one point you're calling `word.word` which is confusing!

Meets Expectations

Below Expectations
