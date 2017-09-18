# Word Watch Submission

Developer: Ben R.
Evaluated by: Schutte

## Repo

* https://github.com/Benja-Ross/word_watch

## Self Assessment Rubric

*Of "Above", "Meets", and "Below" expectations, describe why you deserve which one.*

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

**Meets Expectations

I completed all the challenges. I am choosing not to assess myself as above expectations because there was at least one bug that I noticed. If the paragraph I submitted was very long, then it would split into multiple paragraphs, each on being analyzed separately so words would appear multiple times.

### 2. Code quality
  * Developer breaks functions out into separate responsibilities for:
    * DOM manipulation
    * API interactions
    * data processing
  * Developer has no functions that exceed 8 lines.
  * Developer uses `Array.prototype` functions over `for` loops where appropriate.
  * Developer deals with async API requests in a readable, coherent way.

**Meets Expectations

I felt that I broke my functions down into single responsibilities fairly well. My functions are short. I did however use for loops and didn't deal with Async scenarios.

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

**Meets Expectations

I felt that I was effective with and readable with DOM manipulation targeting the nodes that I was trying to listen for or manipulate.

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

**Meets Expectations

I felt I kept the same flavor of tofu throughout my code. I consistently used ES5 syntax and didn't stray to ES6. I consistently don't use simicolons. I use camelCase throughout. I scoped variables correctly.

## Rubric

### 1. Completion:
  * At a minimum, developer completes challenges 1-3.

**Above Expectations**

Love the honesty about the bugs, but I'd say those are out of the scope of what
we were looking for. Nice job on this!

### 2. Code quality
  * Developer breaks functions out into separate responsibilities for:
    * DOM manipulation
    * API interactions
    * data processing
  * Developer has no functions that exceed 8 lines.
  * Developer uses `Array.prototype` functions over `for` loops where appropriate.
  * Developer deals with async API requests in a readable, coherent way.

**Meets Expectations**

Something like this:
https://github.com/Benja-Ross/word_watch/blob/master/src/index.js#L19, could be
replaced with `words.forEach`.

### 3. Events and DOM manipulation
  * Developer resgisters event listeners within `document.ready`.
  * Developer targets nodes/elements cleanly using 1 or 2 css selectors.
    * && without heavy use of traversing parents and/or children.

**Meets Expectations**

* Note that this: https://github.com/Benja-Ross/word_watch/blob/master/src/index.js#L92 would be sketchy if you introduced any other text input fields. You should listen for `keyup` on only that text area.

### 4. JS conventions
  * Developer scopes variables appropriately.
  * Developer has consistent use of `var` OR `const` and `let`.
  * Developer has consistent use or non-use of semicolons.
  * Developer has consistent use of function syntax.
    * ...or can speak to why inconsistencies were necessary.
  * Developer names variables using camelCase.
  * Developer names classes and constructor functions using CapitalizedCamelCased.

**Below Expectations**

Your function expressions are not defined with `var`. Make a quick PR to fix that and you'll be at "Meets".When you don't set with `var` or `const` or `let`, the variable gets set as a key on the `window` object, which is not appropriately/safely scoped.

Look into your spacing/tab configuration. If you look at your code on GitHub,
there are some crazy spacings sometimes.

