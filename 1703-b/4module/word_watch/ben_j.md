# Word Watch Submission

Developer: Ben J.

Evaluated by: Schutte

## Repo

* [My Repo](https://github.com/Benjaminpjacobs/word_watch)

## Self Assessment Rubric

*Of "Above", "Meets", and "Below" expectations, describe why you deserve which one.*

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

**Above Expectations

I completed all user stories.

### 2. Code quality
  * Developer breaks functions out into separate responsibilities for:
    * DOM manipulation
    * API interactions
    * data processing
  * Developer has no functions that exceed 8 lines.
  * Developer uses `Array.prototype` functions over `for` loops where appropriate.
  * Developer deals with async API requests in a readable, coherent way.

**Above Expectations

I broke down all functions into separate responsibilities and files for the various functions, including moving all the code out of index.js so it was split into listeners, handlers, utilities and services. Additionally I tracked down a circular dependency whcih was breaking webpack and rectified that.

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

**Meets Expectations

I am not exactly sure how you could above expectation on this one. I am setting all neccessary jquery variables inside my document ready and only targeted nodes using one or 2 css selectors.

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

**Meets Expectations

I consistently user ES6 syntax and correctly only use let within a foreach loop when lexical scopping would have caused problems. Utilize arrow syntax correctly, explicity omitting brackets when I wanted implicit return and retaining them when it was unneccessary. I Correctly and precisely named variables using proper JS convention. The only reason I don't believe this is possibly not above expectation is that I did not use any classes or constructors because I simply did not see the need. Without any data persistence it did not seem neccessary to explicity construct objects. Perhaps I could have created an API class that would have served instead of the two functions that live in that file. Similarly I may have been able to create a TextSubmission class that would have held the data from the submision an internally applied functions to it. Again, for this particular challenge that seemed like overkill, but that is also why I'm in this bracket and not the one above.

## Rubric

Thanks for your thoughtful self-assessment!

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

**Above Expectations**

Nice job!

### 2. Code quality
  * Developer breaks functions out into separate responsibilities for:
    * DOM manipulation
    * API interactions
    * data processing
  * Developer has no functions that exceed 8 lines.
  * Developer uses `Array.prototype` functions over `for` loops where appropriate.
  * Developer deals with async API requests in a readable, coherent way.

**Above Expectations**

Nice job breaking out different files for separation of concerns.

Reach for `reduce` here: https://github.com/Benjaminpjacobs/word_watch/blob/master/src/data_utility.js#L13-L22

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

**Meets Expectations**

Nice job splitting listeners from handlers.

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

**Meets Expectations**

Any reason you use vanilla JS and jQuery here? https://github.com/Benjaminpjacobs/word_watch/blob/master/src/listeners.js#L4-L6 ?

Remember that these jQuery object vars should be prefixed with `$` https://github.com/Benjaminpjacobs/word_watch/blob/master/src/listeners.js#L6

