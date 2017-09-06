# Word Watch Submission

Developer: Padraic
Evaluated by:

## Repo
https://github.com/podoglyph/m4_assessment

## Self Assessment Rubric

*Of "Above", "Meets", and "Below" expectations, describe why you deserve which one.*

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

Above Expectations - I completed more than the first three stories during the alloted timeframe.

### 2. Code quality
  * Developer breaks functions out into separate responsibilities for:
    * DOM manipulation
    * API interactions
    * data processing
  * Developer has no functions that exceed 8 lines.
  * Developer uses `Array.prototype` functions over `for` loops where appropriate.
  * Developer deals with async API requests in a readable, coherent way.

Below Expectations - I didn't refactor longer functions and used loops instead of prototype methods.

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

Above Expectations - I set jquery variables, using a maximum of two selectors, on document.ready and used them throughout the code.

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

Meets Expectations - I consistently used const, let, and var where appropriate. I used consistent syntax and no semi-colons throughout the code and followed JS conventions to the best of my knowledge.

## Rubric

## Notes:

- technically only event listeners need to be bound within a `$(document).ready` - not the whole script
- inconsistencies with `let`/`const` vs `var` - ideally it would all be `var` OR a mix of `let`/`const`
- definitely room to refactor longer functions / file as a whole (into multiple separate files)

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

**Below Expectations**

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
