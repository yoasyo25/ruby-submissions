# Word Watch Submission

Developer: Alex
Evaluated by: Lauren

## Repo

* https://github.com/alex-w-k/word_watch

## Self Assessment Rubric

*Of "Above", "Meets", and "Below" expectations, describe why you deserve which one.*

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

Above Expectations

**Meets Expectations**

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

**Meets Expectations**

Below Expectations

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

Above Expectations

**Meets Expectations**

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

**Meets Expectations**

Below Expectations

## Rubric

## Notes:

- technically only event listeners need to be bound within a `$(document).ready` / `document.addEventListener("DOMContentLoaded"`
- since there's some repeated logic within `$('button').on('click', function()` and `$('textarea').keypress(function(key)`, it'd be worth refactoring to pull that logic out and DRY those functions
- some mixes of `forEach` and `for` loops. I'd try to stay consistent with one (an Array.prototype method is usually prefered over `for` loops)
- lots of mixing between `const`/`let` and `var`. Again, I'd try to be consistent with this
- there's also a lack of consistency with use or non-use of semicolons throughout
- some functions are longer than 8 lines - this is where refactoring would help out
- `appendToDom` is clearing out your `.word-count` box, so no matter what, only your last word in the `countedWords` array will appear on the screen. Not sure if you tested this in the browser while developing, but if you didn't, I'd highly recommend checking your work as you go.

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

(technically all stories were developed towards, but story 2, the most critical one, is not functioning properly due to the last note)

**Meets Expectations**

### 2. Code quality
  * Developer breaks functions out into separate responsibilities for:
    * DOM manipulation
    * API interactions
    * data processing
  * Developer has no functions that exceed 8 lines.
  * Developer uses `Array.prototype` functions over `for` loops where appropriate.
  * Developer deals with async API requests in a readable, coherent way.

**Meets Expectations**

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
