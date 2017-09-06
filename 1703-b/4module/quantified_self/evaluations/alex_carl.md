# Alex and Carl

Frontend Production: https://qs.alexwk.rocks/

Frontend Github: https://github.com/ACC25/quantified-self

Backend Production: https://qs-backend.herokuapp.com/api/v1/

Backend Github: https://github.com/ACC25/qs-express

## Self Assessment Rubric

Please self assess with the rubric below. Provide additional information to explain why you feel your project displays the score you've given yourself.

### Specification Adherence

* 3: Application implements all functionality as defined, but some bugs or strange behavior where features intersect *

Completed all user stories with no major bugs. some slight unexpected behavior.

### Planning and Design

* 3: Team created either a schema or API docs to facilitate implementation of a service. *

Our readme explains what users should be able to access and do.

### Testing

* 3: All back-end functionality is covered by tests. Front-end uses unit tests wherever logic can be separated from interface and network requests. *

All back end functionality is tested. Attempted to test on the front end but too much effort for small coverage so abandoned.

### HTML/UI

* 3: Application is not confusing to use. HTML classes and IDs are kebab case. *

UI is clearly laid out with navigation on both pages.

### JS syntax and Style

* 3: Code logically divided into files. Developer can show examples of good coding practices, like DRY and separation of concerns. Attention payed to indentation and naming. *

Indentation and naming was consistant. Logically sepereated into foods and meals and index.

### Git Workflow

* 3: Team is using the feature branches for small groups of cards, and has a pull request for each feature. Developers that aren't on the team have commented on PRs. *

Not much required conversation work was divided into areas that didn't interact with eachother.

### Project Management

_For this rubric item, please describe how you leveraged the project management tool throughout the duration of your project in addition to scoring yourself._

* 3: Team is using a project management tool to keep their project organized. *

Used waffle effectively to track all user stories.

## Instructor Rubric

### Evaluated By: Schutte

### Notes:

* Nice job on functionality! No major bugs that I saw, but you didn't implement sorting by calories or name.
* No notes on either readme for local setup.
* Would like to see more robust assertions on the API. E.g., `delete` just tests a response value, not if the DB count decreased.
* Could have unit tested some of your JS logic / written more testable JS logic.
* Great UI! Love the checkbox animations.
* Take advantage of webpack: https://github.com/ACC25/quantified-self/blob/development/foods.html#L41
* Checking a boolean to return a boolean. Think about a simpler way to do this: https://github.com/ACC25/quantified-self/blob/development/lib/filter.js#L11-L14
* Great abstractions: https://github.com/ACC25/quantified-self/blob/development/lib/filter.js#L37-L46
* Nice use of Knex on the API 👍
* Break these two new lines: https://github.com/ACC25/qs-express/blob/development/lib/models/meal.js#L18
```js
  static withFoods(id) {
    return database.from('foods')
      .innerJoin('meals_foods', 'foods.id', '=', 'meals_foods.food_id')
      .where('meals_foods.meal_id', '=', id)
      .select('foods.id', 'name', 'calories')
  }
```
* This is the same as nesting `document.ready`'s inside each other: https://github.com/ACC25/quantified-self/blob/development/lib/index.js#L10-L16
* DRY: https://github.com/ACC25/quantified-self/blob/development/lib/filter.js#L122-L130

### Specification Adherence

- **3: Application implements all functionality as defined, but some bugs or strange behavior where features intersect**

### Planning and Design

- **2: Team has some notes on how to implement their service, but someone else couldn't implement it.**

### Testing

- **3: All back-end functionality is covered by tests. Front-end uses unit tests wherever logic can be separated from interface and network requests.**

### HTML/UI

- **4: Team put some effort into styling. HTML features unique IDs, classes and data attributes for DOM traversal.**

### JS syntax and Style

- **3: Code logically divided into files. Developer can show examples of good coding practices, like DRY and separation of concerns. Attention payed to indentation and naming.**

### Git Workflow

- **3: Team is using the feature branches for small groups of cards, and has a pull request for each feature. Developers that aren't on the team have commented on PRs.**

### Project Management

- **3: Team is using a project management tool to keep their project
  organized.**
