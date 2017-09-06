# Word Watch Submission

Developer: Charlie

Evaluated by: Schutte

## Repo

* [word_watch](https://github.com/charliecorrigan/word_watch)

## Self Assessment Rubric

*Of "Above", "Meets", and "Below" expectations, describe why you deserve which one.*

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

**Above Expectations - completed all possible functionality

### 2. Code quality
  * Developer breaks functions out into separate responsibilities for:
    * DOM manipulation
    * API interactions
    * data processing
  * Developer has no functions that exceed 8 lines.
  * Developer uses `Array.prototype` functions over `for` loops where appropriate.
  * Developer deals with async API requests in a readable, coherent way.

**Meets Expectations - code is broken into single task functions and is readable. There is a function that is just over 8 lines, but I don't think it's inappropriate. #countWords() in pastedText.js

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

**Meets Expectations - event listeners are registered within document.ready and elements are targeted clearly using specific selectors

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

**Meets Expectations - conventions are consistent across code

## Rubric

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

**Meets Expectations**

Nice job breaking out the functionality. Thanks for the heads up on the length of `countWords`. I agree with you, those curly brackets and parentheses lines are exceptional.

I did see a for loop where a `forEach` would work, just something to keep in mind.

This:
https://github.com/charliecorrigan/word_watch/blob/master/src/javascript/pastedText.js#L7
is different than `this.words`. To set an "instance" variable in a constructor,
you need to set it as `this.words = []`.

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

**Above Expectations**

Love that you broke out a `listen` function. You could even one-line it with `new PasteText().listen()`.

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

**Meets Expectations**

While using `let` isn't wrong per se, you use it a lot where you should just use
`const`. Always start with `const` and move to `let` if you get an error about
variable reassignment.

Reach for string interpolation here: https://github.com/charliecorrigan/word_watch/blob/master/src/javascript/topWord.js#L13

