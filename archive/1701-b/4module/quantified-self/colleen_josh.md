# Quantified Self

### Students: Colleen Ward and Josh Thompson

### Evaluated by: Schutte

#### Notes

* This was a pleasure to review. Great job!
* Awesome first impression on the production front-end!
* Interesting bug: when there is only one item left in a meal table, my delete
  gets a 404 in the console, but the item is gone if I refresh. Hm...
* Having everything vertically stacked made it a little difficult to use, maybe
  open it up to two columns or have some absolute/fixed content to navigate.
  * Great job with the link to get back to create foods!
* Awesome documentation in the README's.
* Fun JS note:
```js
module.exports = {
  createFoods: createFoods,
  resetFoods: resetFoods,
  findFirst: findFirst,
  find: find,
  findAll: findAll,
  update: update,
  findByName: findByName,
  setInactive: setInactive
}
```

can be written with a shorthand:

```js
module.exports = {
  createFoods,
  resetFoods,
  findFirst,
  find,
  findAll,
  update,
  findByName,
  setInactive
}
```

*as long as the key/value names are identical*.

## Rubric

You will be subjectively graded by an instructor on the following criteria:

### Specification Adherence

- 3: Application implements all functionality as defined, but some bugs or strange behavior where features intersect
p
### Planning and Design

- **3: Team created either a schema or API docs to facilitate implementation of a service.**

### Testing

- **2: More back-end functionality implemented than tested and/or very little front-end testing**

### HTML/UI

- **4: Team put some effort into styling. HTML features unique IDs, classes and data attributes for DOM traversal.**

### JS syntax and Style

- **3: Code logically divided into files. Developer can show examples of good coding practices, like DRY and separation of concerns. Attention payed to indentation and naming.**

### Git Workflow

- **3: Team is using the feature branches for small groups of cards, and has a pull request for each feature. Developers that aren't on the team have commented on PRs.**

### Project Management

- **3: Team is using a project management tool to keep their project
  organized.**

