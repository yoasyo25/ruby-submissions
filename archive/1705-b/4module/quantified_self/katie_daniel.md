# Katie & Daniel


Frontend Production: https://katiekeel.github.io/quantified-self/

Frontend Github: https://github.com/katiekeel/quantified-self

Backend Production: https://qs-express-api.herokuapp.com/

Backend Github: https://github.com/katiekeel/qs-express-api/tree/master


## Self Assessment Rubric

Please self assess with the rubric below. Provide additional information to explain why you feel your project displays the score you've given yourself in _each_ section.

### Specification Adherence

Application implements **all** functionality as defined, but some bugs or strange behavior where features intersect.

- Meets Expectations

### Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application.

- Meets Expectations

README has implemented these requirements.

### HTML/UI

The team put some effort into styling, and the application is not confusing to use. HTML classes and IDs are kebab case.

- Above Expectations

### Accessibility

Developer implements code to increase accessibility.

- Meets Expectations

### JS syntax and Style

JavaScript code is logically divided into files. Developers can show examples of good coding practices and demonstrate OOP concepts, like DRY and separation of concerns. Developers pay attention to indentation and naming conventions. They also consistently utilize ES5 or ES6 syntax and jQuery when working with events.

- Above Expectations

### Git Workflow

The team uses master for production, uses feature branches for small groups of cards, and has a pull request for each feature with good context and conversation. Developers that aren't on the team have commented on PRs.

- Meets Expectations

Very nice job of communicating through github comments and we stayed on sub-branches always when developing new features.

### Project Management

The team is using a project management tool to keep their project organized and to track progress. Team is documenting conclusions and timelines on relevant cards.

- Above Expectations

Waffle, github, and slack

### Communication

The team consistently reaches out to their Technical Lead for feedback on code quality and technical issues. The team responds to their Technical Lead in a timely manner.

- Above Expectations

Great communicators and consistently willing to work to find middle ground.

-----------

## Instructor Rubric


### Evaluated By: Katelyn

### Notes:
- Cannot delete a food from foods that belongs to a meal, should give the user a message or iterate through the meals and delete it

- Food not sorted by calorie count correctly ex. order 300, 42, 45, 520 based on alphabetic problem vs numeric. Very strange as it only happens the 1st time sorting is started

- Sorting should have be done without an outside library

- Would have liked to see alt tags with the image of delete button

- Love all the tests on the backend :+1:

- Good job on the collaborations on the PRs

- Typically with documentation you have included install instructions on the specific repo they are referring to. So, I would expect to see the API instructions on `qs-express-api` Repo

- Would have also liked to see api endpoint docs

- Inconsistent semi colons, anonymous document ready calls

- A bit of weird file structure for example `mealsAjax.js` I would have had functions with the ajax calls, exported them and then called document ready in a different file calling those functions

- Document ready calls are all over the place, hard to figure out what is happening when the application starts

**Having to have a local branch for local dev is unacceptable. Should have used a Procfile for Heroku. It would be incredibly annoying to have to always copy over changes to both branches**

- Should not be checking `node_modules` into git especially with heroku

### Specification Adherence

Application implements **all** functionality as defined, but some bugs or strange behavior where features intersect.

**Meets Expectations**

### Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application.

**Meets Expectations**

### HTML/UI

The team put some effort into styling, and the application is not confusing to use. HTML classes and IDs are kebab case.

**Meets Expectations**

### Accessibility

Developer implements code to increase accessibility.

**Meets Expectations**

### JS syntax and Style

JavaScript code is logically divided into files. Developers can show examples of good coding practices and demonstrate OOP concepts, like DRY and separation of concerns. Developers pay attention to indentation and naming conventions. They also consistently utilize ES5 or ES6 syntax and jQuery when working with events.

**Below Expectations**

### Git Workflow

The team uses master for production, uses feature branches for small groups of cards, and has a pull request for each feature with good context and conversation. Developers that aren't on the team have commented on PRs.

**Meets Expectations**

### Project Management

The team is using a project management tool to keep their project organized and to track progress. Team is documenting conclusions and timelines on relevant cards.

**Above Expectations**

### Communication

The team consistently reaches out to their Technical Lead for feedback on code quality and technical issues. The team responds to their Technical Lead in a timely manner.

**Meets Expectations**
