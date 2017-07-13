# Quantified Self

### Students:

### Evaluated by:

#### Notes

* 

## Rubric

You will be subjectively graded by an instructor on the following criteria:

### Specification Adherence

- 4: Application implements all functionality as defined, with no bugs, and one extension (if you choose to put your point here)
- 3: Application implements all functionality as defined, but some bugs or strange behavior where features intersect
- 2: Application is missing required functionality, deviates significantly from the spec, or serious bugs prevent features from being usable
- 1: Application is missing a significant portion of functionality

### Planning and Design

- 4: Team created visual schema, API documentation and user stories, before writing tests. API adheres to REST standard.
- 3: Team created either a schema or API docs to facilitate implementation of a service.
- 2: Team has some notes on how to implement their service, but someone else couldn't implement it.
- 1: Team did not design their service.

### Testing

- 4: All functionality is covered by tests. Appropriate mix of unit and integration tests. Sad path testing in both unit and integration tests.
- 3: All back-end functionality is covered by tests. Front-end uses unit tests wherever logic can be separated from interface and network requests.
- 2: More back-end functionality implemented than tested and/or very little front-end testing
- 1: Team fails to effectively test the application.

### HTML/UI

- 4: Team put some effort into styling. HTML features unique IDs, classes and data attributes for DOM traversal.
- 3: Application is not confusing to use. HTML classes and IDs are kebab case.
- 2: HTML is greatly lacking in standards compliance. UI is confusing or very buggy.
- 1: Application is unusable

### JS syntax and Style

- 4: Javascript features explicit DOM traversal (not using closest), demonstrates great OOP concepts, and uses named and anonymous functions when appropriate
- 3: Code logically divided into files. Developer can show examples of good coding practices, like DRY and separation of concerns. Attention payed to indentation and naming.
- 2: Javascript is noticeably lacking in the above concepts.
- 1: Team has not applied any style concepts from class or from Ruby background

### Git Workflow

- 4: Team uses master for production, and creates a feature branch for each card worked on. Team is using pull requests with good context and conversation
- 3: Team is using the feature branches for small groups of cards, and has a pull request for each feature. Developers that aren't on the team have commented on PRs.
- 2: Team fails to use feature branches, or isn't using pull requests
- 1: All code is committed to master

### Project Management

- 4: Team is using a project management tool and updating their progress daily. Team is approving each other's  work. Team is documenting conversations and conclusions on relevant cards.
- 3: Team is using a project management tool to keep their project organized.
- 2: Team is using a project management tool but didn't update the progress frequently. Many cards have no changes made to them
- 1: Team failed to use a project management tool to track its progress.

### Risk Taking

Adhering to any of these additional specifications will allow you to increase one score above:

#### All functionality is part of a class, written using ES6

You'll learn about classes and ES6 during the course of this project. If you can fit all of your JS into classes, using ES6 syntax, you'll get one extra point to add to a rubric score.

#### No Libraries (except for testing).

A big part of this project is writing JS functionality that you could have borrowed from a library. We've listed a few allowed libraries above. jQuery is still used in most legacy codebases, and JS is sorely missing most time manipulation. Accepting this challenge will require you to write more code, but it will give you a better handle one what is built into JS.

The exception is testing. There's not any reasonable way you'll be able to test without mocha and selenium.

#### Multiple Sources of Truth

Local Storage is often used for "offline" functionality. When the user is having trouble connecting to the internet, the application will continue to function. When a connection is re-established, the local changes are uploaded to the server. Likewise, if changes are made on one client, they should be downloaded to another client

Use Local Storage and AJAX to meet the following requirements:

1. If I'm disconnected from the internet, I can continue to use the application.
1. When I make a change while disconnected from the internet, that change will be uploaded to the server when I reconnect
2. If I make a change on one computer, those changes should propagate to any other clients through the server. You do not need realtime functionality. These changes can occur after a refresh.

You will probably need to use a concept called `service workers`

#### Mircroservices

Instead of building a single service, build a series of microservices. Each microservice is a separate codebase and application that represents a single table in your schema. These applications communicate with each other via HTTP. Since they all live in the same datacenter, this is not much of a performance problem.

The architecture would look something like this:

![microservices-challenge](./microservices-challenge.png)

If you attempt this challenge, your planning and design should include your microservices architecture.

As to why you might want to do this, watch [Chad Fowler's Rocky Mountain Ruby 2015 talk](https://www.youtube.com/watch?v=-UKEPd2ipEk)

