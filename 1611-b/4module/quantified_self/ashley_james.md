# Ashley & James

* Backend Github Link: https://github.com/AELSchauer/quantified-self-be
* Frontend Github Link: https://github.com/AELSchauer/quantified-self-fe
* Frontend Production Link: https://aelschauer.github.io/quantified-self-fe/

## Rubric

You will be subjectively graded by an instructor on the following criteria:

### Specification Adherence

- 4: Application implements all functionality as defined, with no bugs, and one extension
- **3: Application implements all functionality as defined, but some bugs or strange behavior where features intersect**
- 2: Application is missing required functionality, deviates significantly from the spec, or serious bugs prevent features from being usable
- 1: Application is missing a significant portion of functionality

*Adding a food is actually reloading the page, other than that food page works well
Small validation error where if I enter the calories I'm allowed to enter a negative amount.
Diaries page looks really good.  I caught a small error where if I add a food to a diary, and then remove it the total calories and remaining calories field are not updated.*

### Planning and Design

- 4: Team created visual schema, API documentation and user stories, before writing tests. API adheres to REST standard.
- **3: Team created either a schema or API docs to facilitate implementation of a service.**
- 2: Team has some notes on how to implement their service, but someone else couldn't implement it.
- 1: Team did not design their service.

*Your documentation isn't good, it's great!  Did you create a schema before hand?  If so I would bump this to a 4.*

### Testing

- 4: All functionality is covered by tests. Appropriate mix of unit and integration tests. Sad path testing in both unit and integration tests.
- **3: All back-end functionality is covered by tests. Front-end uses unit tests wherever logic can be separated from interface and network requests.**
- 2: More back-end functionality implemented than tested and/or very little front-end testing
- 1: Team fails to effectively test the application.

3.5.  *I appreciate that you wrote some intergration tests that worked!  I am getting one failing tests for one of the integration tests.
Good job on the backend tests!  It is very well tested, the functionality tested is appropriate.  Nice helper function DateHelper for your tests.*

### HTML/UI

- 4: Team put some effort into styling. HTML features unique IDs, classes and data attributes for DOM traversal.
- **3: Application is not confusing to use. HTML classes and IDs are kebab case.**
- 2: HTML is greatly lacking in standards compliance. UI is confusing or very buggy.
- 1: Application is unusable

*Pretty good UX.  The styling is better than most of the QS apps I've seen.  Would be nice to have a navigation link
back to the home page/diaries page from the foods page.  Adding new foods is below the fold, would be nice if there
was a more user friendly layout.*

### JS syntax and Style

- 4: Javascript features explicit DOM traversal (not using closest), demonstrates great OOP concepts, and uses named and anonymous functions when appropriate
- **3: Code logically divided into files. Developer can show examples of some SOLID concepts. Attention payed to indentation and naming.**
- 2: Javascript is noticeably lacking in the above concepts.
- 1: Team has not applied any style concepts from class or from Ruby background

3.5 *I like the use of object destructuring in a lot of you files.  Good use of ES6 syntax.  I like the experimentation with using some of the knex built it querying language instead of writing raw sql for all your queries. Also you did generally a good job of organizing files.*

### Git Workflow

- 4: Team uses master for production, and creates a feature branch for each card worked on. Team is using pull requests with good context and conversation
- **3: Team is using the feature branches for small groups of cards, and has a pull request for each feature. Developers that aren't on the team have commented on PRs.**
- 2: Team fails to use feature branches, or isn't using pull requests
- 1: All code is committed to master

*I would say your commit messages are clearer than most I've seen.  A recommendation is to have one feature per branch you merge in.
A feature should be something like 'get-all-foods' that is just for one endpoint.  All the commits should be squashed to keep the git history clean.*

### Project Management

- 4: Team is using a project management tool and updating their progress daily. Team is approving each other's  work. Team is documenting conversations and conclusions on relevant cards.
- **3: Team is using a project management tool to keep their project organized.**
- 2: Team is using a project management tool but didn't update the progress frequently. Many cards have no changes made to them
- 1: Team failed to use a project management tool to track its progress.
