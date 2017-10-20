# Charlie and Aaron

[Frontend Production:](https://charliecorrigan.github.io/quantify-this/)

[Frontend Github:](https://github.com/charliecorrigan/quantify-this)

[Backend Production:](quantify-this-api-express.herokuapp.com)

[Backend Github:](https://github.com/MrAaronOlsen/quantify-this-api-js)

## Self Assessment Rubric

_Self assessment notes are on the PR submitted, not located in this file._

Please self assess with the rubric below. Provide additional information to explain why you feel your project displays the score you've given yourself.

### Specification Adherence

- 4: Application implements all functionality as defined, with no bugs, and one extension (if you choose to put your point here)
* 3: Application implements all functionality as defined, but some bugs or strange behavior where features intersect
- 2: Application is missing required functionality, deviates significantly from the spec, or serious bugs prevent features from being usable
- 1: Application is missing a significant portion of functionality

### Planning and Design

- 4: Team created visual schema, API documentation and user stories, before writing tests. API adheres to REST standard.
* 3: Team created either a schema or API docs to facilitate implementation of a service.
- 2: Team has some notes on how to implement their service, but someone else couldn't implement it.
- 1: Team did not design their service.

### Testing

- 4: All functionality is covered by tests. Appropriate mix of unit and integration tests. Sad path testing in both unit and integration tests.
* 3: All back-end functionality is covered by tests. Front-end uses unit tests wherever logic can be separated from interface and network requests.
- 2: More back-end functionality implemented than tested and/or very little front-end testing
- 1: Team fails to effectively test the application.

### HTML/UI

* 4: Team put some effort into styling. HTML features unique IDs, classes and data attributes for DOM traversal.
- 3: Application is not confusing to use. HTML classes and IDs are kebab case.
- 2: HTML is greatly lacking in standards compliance. UI is confusing or very buggy.
- 1: Application is unusable

### JS syntax and Style

* 4: Javascript features explicit DOM traversal (not using closest), demonstrates great OOP concepts, and uses named and anonymous functions when appropriate
- 3: Code logically divided into files. Developer can show examples of good coding practices, like DRY and separation of concerns. Attention payed to indentation and naming.
- 2: Javascript is noticeably lacking in the above concepts.
- 1: Team has not applied any style concepts from class or from Ruby background

### Git Workflow

* 4: Team uses master for production, and creates a feature branch for each card worked on. Team is using pull requests with good context and conversation
- 3: Team is using the feature branches for small groups of cards, and has a pull request for each feature. Developers that aren't on the team have commented on PRs.
- 2: Team fails to use feature branches, or isn't using pull requests
- 1: All code is committed to master

### Project Management

_For this rubric item, please describe how you leveraged the project management tool throughout the duration of your project in addition to scoring yourself._

- 4: Team is using a project management tool and updating their progress daily. Team is approving each other's  work. Team is documenting conversations and conclusions on relevant cards.
* 3: Team is using a project management tool to keep their project organized.
- 2: Team is using a project management tool but didn't update the progress frequently. Many cards have no changes made to them
- 1: Team failed to use a project management tool to track its progress.

## Instructor Rubric

### Evaluated By: Casey

### Notes:

_See notes under each section._

### Specification Adherence

- 4: Application implements all functionality as defined, with no bugs, and one extension (if you choose to put your point here)
- **3: Application implements all functionality as defined, but some bugs or strange behavior where features intersect**
- 2: Application is missing required functionality, deviates significantly from the spec, or serious bugs prevent features from being usable
- 1: Application is missing a significant portion of functionality

_All functionality has been implemented and works well!_

### Planning and Design

- 4: Team created visual schema, API documentation and user stories, before writing tests. API adheres to REST standard.
- **3: Team created either a schema or API docs to facilitate implementation of a service.**
- 2: Team has some notes on how to implement their service, but someone else couldn't implement it.
- 1: Team did not design their service.

_You have API documentation and your API follows the REST standard. I would have loved to see a schema (but then again you already had the Rails API and knew what you needed)._

### Testing

- 4: All functionality is covered by tests. Appropriate mix of unit and integration tests. Sad path testing in both unit and integration tests.
- **3: All back-end functionality is covered by tests. Front-end uses unit tests wherever logic can be separated from interface and network requests.**
- 2: More back-end functionality implemented than tested and/or very little front-end testing
- 1: Team fails to effectively test the application.

_The tests that you do have look solid. I know y'all had trouble with your post tests so this item will remain a three!_

### HTML/UI

- **4: Team put some effort into styling. HTML features unique IDs, classes and data attributes for DOM traversal.**
- 3: Application is not confusing to use. HTML classes and IDs are kebab case.
- 2: HTML is greatly lacking in standards compliance. UI is confusing or very buggy.
- 1: Application is unusable

_Your UI is pretty awesome. You put a lot of effort into styling and your app is easy to use and looks wonderful._

### JS syntax and Style

- **4: Javascript features explicit DOM traversal (not using closest), demonstrates great OOP concepts, and uses named and anonymous functions when appropriate**
- 3: Code logically divided into files. Developer can show examples of good coding practices, like DRY and separation of concerns. Attention payed to indentation and naming.
- 2: Javascript is noticeably lacking in the above concepts.
- 1: Team has not applied any style concepts from class or from Ruby background

_You explicitly traverse and manipulate the DOM and your code demonstrates good OOP concepts. You've broken your code into functions/files that are easy to navigate and understand. I see y'all have an "html" file - it may be helpful to think of the MVC pattern next time when you're developing a JS frontend application. It might be more intuitive/easy to organize to follow MVC!_

### Git Workflow

- 4: Team uses master for production, and creates a feature branch for each card worked on. Team is using pull requests with good context and conversation
- **3: Team is using the feature branches for small groups of cards, and has a pull request for each feature. Developers that aren't on the team have commented on PRs.**
- 2: Team fails to use feature branches, or isn't using pull requests
- 1: All code is committed to master

_I like that y'all used TravisCI and were diligent about creating branches and keeping master up to date. I would have liked to see even more conversation on your PR's. I also didn't receive many questions from y'all on PR's (which is totally fine if you didn't need help), but it's always to get outside opinions even if it's just refactoring pointers._

### Project Management

- 4: Team is using a project management tool and updating their progress daily. Team is approving each other's  work. Team is documenting conversations and conclusions on relevant cards.
- **3: Team is using a project management tool to keep their project organized.**
- 2: Team is using a project management tool but didn't update the progress frequently. Many cards have no changes made to them
- 1: Team failed to use a project management tool to track its progress.

_You used PT to track stories and gauge progress sufficiently._
