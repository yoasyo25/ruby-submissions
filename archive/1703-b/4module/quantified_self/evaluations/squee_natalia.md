# Natalia and Squee

Frontend Production: [qs githubpages](https://squeemishly.github.io)

Frontend Github: [qs frontend](https://github.com/squeemishly/quantified-self)

Backend Production: [qs-api heroku](https://qs-api-nc-sl.herokuapp.com)

Backend Github: [qs api](https://github.com/nmcolome/qs-js-api)

## Self Assessment Rubric

Please self assess with the rubric below. Provide additional information to explain why you feel your project displays the score you've given yourself.

### Specification Adherence

- 4: Application implements all functionality as defined, with no bugs, and one extension (if you choose to put your point here)
**- 3: Application implements all functionality as defined, but some bugs or strange behavior where features intersect: The application works as defined, it does not have bugs or strange behavior, we just did not add an extension**
- 2: Application is missing required functionality, deviates significantly from the spec, or serious bugs prevent features from being usable
- 1: Application is missing a significant portion of functionality

### Planning and Design

**- 4: Team created visual schema, API documentation and user stories, before writing tests. API adheres to REST standard. You can find schema at http://ondras.zarovi.cz/sql/demo/?=keyword=quantified_self, it has a ReadMe and stories on Waffle**
- 3: Team created either a schema or API docs to facilitate implementation of a service.
- 2: Team has some notes on how to implement their service, but someone else couldn't implement it.
- 1: Team did not design their service.

### Testing

- 4: All functionality is covered by tests. Appropriate mix of unit and integration tests. Sad path testing in both unit and integration tests.
**- 3: All back-end functionality is covered by tests. Front-end uses unit tests wherever logic can be separated from interface and network requests. Frontend has all the unit tests we could do, but only a few feature tests. Backend ran into errors testing meals and even though we dedicated 2 afternoons, we couldn't move past it. Tested with postman and clicking on localhost to double check. We did test for sad/happy paths**
- 2: More back-end functionality implemented than tested and/or very little front-end testing
- 1: Team fails to effectively test the application.

### HTML/UI

**- 4: Team put some effort into styling. HTML features unique IDs, classes and data attributes for DOM traversal. We tried to format it so you could see everything without scrolling and the delete buttons (x) to stand out.**
- 3: Application is not confusing to use. HTML classes and IDs are kebab case.
- 2: HTML is greatly lacking in standards compliance. UI is confusing or very buggy.
- 1: Application is unusable

### JS syntax and Style

- 4: Javascript features explicit DOM traversal (not using closest), demonstrates great OOP concepts, and uses named and anonymous functions when appropriate
**- 3: Code logically divided into files. Developer can show examples of good coding practices, like DRY and separation of concerns. Attention payed to indentation and naming.**
- 2: Javascript is noticeably lacking in the above concepts.
- 1: Team has not applied any style concepts from class or from Ruby background

### Git Workflow

**- 4: Team uses master for production, and creates a feature branch for each card worked on. Team is using pull requests with good context and conversation: We used it to ask questions at one point, but we ended getting feedback face to face**
- 3: Team is using the feature branches for small groups of cards, and has a pull request for each feature. Developers that aren't on the team have commented on PRs.
- 2: Team fails to use feature branches, or isn't using pull requests
- 1: All code is committed to master

### Project Management

_For this rubric item, please describe how you leveraged the project management tool throughout the duration of your project in addition to scoring yourself._

**- 4: Team is using a project management tool and updating their progress daily. Team is approving each other's  work. Team is documenting conversations and conclusions on relevant cards.: We used two Waffle boards, one for the API and one for the frontend, we kept it updated**
- 3: Team is using a project management tool to keep their project organized.
- 2: Team is using a project management tool but didn't update the progress frequently. Many cards have no changes made to them
- 1: Team failed to use a project management tool to track its progress.

## Instructor Rubric

### Evaluated By: Lauren

### Notes:

Job well done! A few notes:

- JS is organized really nicely throughout both repos
- great ES6, promise chaining
- could be worth making your file-naming styles consistent (I'm seeing snake_case, kebab-case, and camelCase)
- from a usability standpoint, it could be nice to make clearer when foods are editable and when they're not (foods page vs counter page)
- a little more TLC in the styling department would make this more appealing on your portfolio

### Specification Adherence

- **4: Application implements all functionality as defined, with no bugs, and one extension (if you choose to put your point here)**

### Planning and Design

**- 4: Team created visual schema, API documentation and user stories, before writing tests. API adheres to REST standard.**

### Testing

**- 3: All back-end functionality is covered by tests. Front-end uses unit tests wherever logic can be separated from interface and network requests.**

### HTML/UI

**- 3: Application is not confusing to use. HTML classes and IDs are kebab case.**

### JS syntax and Style

**- 4: Javascript features explicit DOM traversal (not using closest), demonstrates great OOP concepts, and uses named and anonymous functions when appropriate**

### Git Workflow

**- 4: Team uses master for production, and creates a feature branch for each card worked on. Team is using pull requests with good context and conversation**

### Project Management

**- 4: Team is using a project management tool and updating their progress daily. Team is approving each other's  work. Team is documenting conversations and conclusions on relevant cards.**
