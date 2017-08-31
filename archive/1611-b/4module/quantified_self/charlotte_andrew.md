# Andrew & Charlotte

* Backend Github Link:https://github.com/CjMoore/quantified-self-be
* Frontend Github Link:https://github.com/CjMoore/quantified-self
* Frontend Production Link:https://cjmoore.github.io/quantified-self/

## Rubric

You will be subjectively graded by an instructor on the following criteria:

### Specification Adherence

- 4: Application implements all functionality as defined, with no bugs, and one extension
- **3: Application implements all functionality as defined, but some bugs or strange behavior where features intersect**
- 2: Application is missing required functionality, deviates significantly from the spec, or serious bugs prevent features from being usable
- 1: Application is missing a significant portion of functionality

*I'm really impressed with this app overall.  Great job!
I can enter in negative calories for a food :( otherwise I think it's a 4*

### Planning and Design

- 4: Team created visual schema, API documentation and user stories, before writing tests. API adheres to REST standard.
- **3: Team created either a schema or API docs to facilitate implementation of a service.**
- 2: Team has some notes on how to implement their service, but someone else couldn't implement it.
- 1: Team did not design their service.

*Willing to bump this to a 4 if you can get me a schema.  I couldn't open the one in the README Good documenation.*

### Testing

- 4: All functionality is covered by tests. Appropriate mix of unit and integration tests. Sad path testing in both unit and integration tests.
- **3: All back-end functionality is covered by tests. Front-end uses unit tests wherever logic can be separated from interface and network requests.**
- 2: More back-end functionality implemented than tested and/or very little front-end testing
- 1: Team fails to effectively test the application.

*I know unit tests for the front end we're difficult to get up and running. Backend tests are sufficent.  I would like to see response codes tests for a succsessful post, or a unprocessable entity.  I get two failing unit tests for the backend*

### HTML/UI

- **4: Team put some effort into styling. HTML features unique IDs, classes and data attributes for DOM traversal.**
- 3: Application is not confusing to use. HTML classes and IDs are kebab case.
- 2: HTML is greatly lacking in standards compliance. UI is confusing or very buggy.
- 1: Application is unusable

*Y'all! These checkboxes are mad fresh. Losing my shit over here.  Everything is well styled, the UX makes a lot of sense.
Well designed, only small demerit is there should be a way for me to navigate back to the homepage without clicking on the back button.*

### JS syntax and Style

- 4: Javascript features explicit DOM traversal (not using closest), demonstrates great OOP concepts, and uses named and anonymous functions when appropriate
- **3: Code logically divided into files. Developer can show examples of some SOLID concepts. Attention payed to indentation and naming.**
- 2: Javascript is noticeably lacking in the above concepts.
- 1: Team has not applied any style concepts from class or from Ruby background

*Not really syntax or style, but I would pass in the values directly into the model instead of passing the params object. Good use of ES6 syntax like fat arrows.
Find meals function is a little bit gnarly and could use a refactor. Other than that good clean code, good separation of files and concerns.*

### Git Workflow

- 4: Team uses master for production, and creates a feature branch for each card worked on. Team is using pull requests with good context and conversation
- **3: Team is using the feature branches for small groups of cards, and has a pull request for each feature. Developers that aren't on the team have commented on PRs.**
- 2: Team fails to use feature branches, or isn't using pull requests
- 1: All code is committed to master

*I think Good use of feature branches and pull requests.  I have a few suggestions about some of your git workflow.
It would be nice if each feature branch is smaller.  For example you have one called 'api-diary-endpoints'.
There should be separate branches for each of those diary-endpoints.  For example 'get-all-diaries'.  Also it is good practice
not to litter your commit history.  For instance update README.md there are multiple commits with that message.
Try using `git commit --amend` this will let you keep the same commit message as your previous commit.  I would also
look into squashing.*

### Project Management

- 4: Team is using a project management tool and updating their progress daily. Team is approving each other's  work. Team is documenting conversations and conclusions on relevant cards.
- **3: Team is using a project management tool to keep their project organized.**
- 2: Team is using a project management tool but didn't update the progress frequently. Many cards have no changes made to them
- 1: Team failed to use a project management tool to track its progress.
