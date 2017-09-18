# Rhonda, Ben, and Will

Frontend Production: https://benja-ross.github.io/quantified-self/

Frontend Github: https://github.com/Benja-Ross/quantified-self

Backend Production: https://lit-basin-44778.herokuapp.com/

Backend Github: https://github.com/Benja-Ross/node-quantified-self-api

## Self Assessment Rubric

Please self assess with the rubric below. Provide additional information to explain why you feel your project displays the score you've given yourself.

### Specification Adherence

- 4: Application implements all functionality as defined, with no bugs, and one extension (if you choose to put your point here)
*** 3: Application implements all functionality as defined, but some bugs or strange behavior where features intersect
- 2: Application is missing required functionality, deviates significantly from the spec, or serious bugs prevent features from being usable
- 1: Application is missing a significant portion of functionality

Our application implements all functionality as defined, but is experiencing some buggy behavior with the sorting feature. 

### Planning and Design

*** 4: Team created visual schema, API documentation and user stories, before writing tests. API adheres to REST standard.
- 3: Team created either a schema or API docs to facilitate implementation of a service.
- 2: Team has some notes on how to implement their service, but someone else couldn't implement it.
- 1: Team did not design their service.

Our team created and heavily utilized a visual db schema and wrote API documentation for an API that adheres to REST.

### Testing

- 4: All functionality is covered by tests. Appropriate mix of unit and integration tests. Sad path testing in both unit and integration tests.
*** 3: All back-end functionality is covered by tests. Front-end uses unit tests wherever logic can be separated from interface and network requests.
- 2: More back-end functionality implemented than tested and/or very little front-end testing
- 1: Team fails to effectively test the application.

We wrote extensive back-end tests and front-end tests in areas that didn't require communication with the back end.

### HTML/UI

*** 4: Team put some effort into styling. HTML features unique IDs, classes and data attributes for DOM traversal.
- 3: Application is not confusing to use. HTML classes and IDs are kebab case.
- 2: HTML is greatly lacking in standards compliance. UI is confusing or very buggy.
- 1: Application is unusable

We implemented styling with attention to user experience along with differentiated class/ID naming for ease of DOM traversal.

### JS syntax and Style

- 4: Javascript features explicit DOM traversal (not using closest), demonstrates great OOP concepts, and uses named and anonymous functions when appropriate
*** 3: Code logically divided into files. Developer can show examples of good coding practices, like DRY and separation of concerns. Attention payed to indentation and naming.
- 2: Javascript is noticeably lacking in the above concepts.
- 1: Team has not applied any style concepts from class or from Ruby background

We broke out the JS code into separate files and DRY'ed it out in several areas.

### Git Workflow

*** 4: Team uses master for production, and creates a feature branch for each card worked on. Team is using pull requests with good context and conversation
- 3: Team is using the feature branches for small groups of cards, and has a pull request for each feature. Developers that aren't on the team have commented on PRs.
- 2: Team fails to use feature branches, or isn't using pull requests
- 1: All code is committed to master

### Project Management

_For this rubric item, please describe how you leveraged the project management tool throughout the duration of your project in addition to scoring yourself._

*** 4: Team is using a project management tool and updating their progress daily. Team is approving each other's  work. Team is documenting conversations and conclusions on relevant cards.
- 3: Team is using a project management tool to keep their project organized.
- 2: Team is using a project management tool but didn't update the progress frequently. Many cards have no changes made to them
- 1: Team failed to use a project management tool to track its progress.

We made great use of Pivotal Tracker for features and chores. We also maintained excellent Git workflow with separate branches and thorough pull request reviews.

## Instructor Rubric

### Evaluated By: Casey

### Notes:

_See notes in each section._

### Specification Adherence

- 4: Application implements all functionality as defined, with no bugs, and one extension (if you choose to put your point here)
- 3: Application implements all functionality as defined, but some bugs or strange behavior where features intersect
- **2: Application is missing required functionality, deviates significantly from the spec, or serious bugs prevent features from being usable**
- 1: Application is missing a significant portion of functionality

_The edit functionality is broken and I don't see the sorting by calories functionality present._

### Planning and Design

- 4: Team created visual schema, API documentation and user stories, before writing tests. API adheres to REST standard.
- **3: Team created either a schema or API docs to facilitate implementation of a service.**
- 2: Team has some notes on how to implement their service, but someone else couldn't implement it.
- 1: Team did not design their service.

_I don't see a visual schema in either repo, but you do have API docs and your API follows RESTful conventions which looks solid._

### Testing

- 4: All functionality is covered by tests. Appropriate mix of unit and integration tests. Sad path testing in both unit and integration tests.
- **3: All back-end functionality is covered by tests. Front-end uses unit tests wherever logic can be separated from interface and network requests.**
- 2: More back-end functionality implemented than tested and/or very little front-end testing
- 1: Team fails to effectively test the application.

_Backend tests are pending (Will mentioned that instructors told y'all to move on) and frontend has several unit and integration tests. The tests look solid and well-organized._

### HTML/UI

- **4: Team put some effort into styling. HTML features unique IDs, classes and data attributes for DOM traversal.**
- 3: Application is not confusing to use. HTML classes and IDs are kebab case.
- 2: HTML is greatly lacking in standards compliance. UI is confusing or very buggy.
- 1: Application is unusable

_The user interface is great. It's easy to navigate and pleasant to use. HTML is structured in a well-organized way._

### JS syntax and Style

- 4: Javascript features explicit DOM traversal (not using closest), demonstrates great OOP concepts, and uses named and anonymous functions when appropriate
- 3: Code logically divided into files. Developer can show examples of good coding practices, like DRY and separation of concerns. Attention payed to indentation and naming.
- **2: Javascript is noticeably lacking in the above concepts.**
- 1: Team has not applied any style concepts from class or from Ruby background

_There are variables named with both snake and camel case and y'all switch from using const and let to using var within the same file. There are more than a few long functions that need refactoring to separate concerns and reuse code. You have a "filterFoods" function defined in more than one place. There's also several places where selecting nodes on the DOM is messy - see below_

```js
var foodID = this.parentElement.parentElement.parentElement.childNodes[0].dataset.id
var mealElement = this.parentElement.parentElement.parentElement.parentElement.parentElement
```

### Git Workflow

- 4: Team uses master for production, and creates a feature branch for each card worked on. Team is using pull requests with good context and conversation
- **3: Team is using the feature branches for small groups of cards, and has a pull request for each feature. Developers that aren't on the team have commented on PRs.**
- 2: Team fails to use feature branches, or isn't using pull requests
- 1: All code is committed to master

_You used branches and pull requests which is great! I would have liked to see more comments on Pull Requests to give each other feedback on specific lines of code._

### Project Management

- 4: Team is using a project management tool and updating their progress daily. Team is approving each other's  work. Team is documenting conversations and conclusions on relevant cards.
- **3: Team is using a project management tool to keep their project organized.**
- 2: Team is using a project management tool but didn't update the progress frequently. Many cards have no changes made to them
- 1: Team failed to use a project management tool to track its progress.

_Team used PT to track the project, stay organize, and prioritize._
