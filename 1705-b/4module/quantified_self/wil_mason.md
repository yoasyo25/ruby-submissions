# Wil & Mason

Frontend Production:
https://MasonHolland.github.io/quantified-self

Frontend Github:
https://github.com/MasonHolland/quantified-self

Backend Production:
https://fast-thicket-80204.herokuapp.com

Backend Github:
https://github.com/swdonovan/node-qs-api

## Self Assessment Rubric

Please self assess with the rubric below. Provide additional information to explain why you feel your project displays the score you've given yourself in _each_ section.

### Specification Adherence

Application implements **all** functionality as defined, but some bugs or strange behavior where features intersect.


- Meets Expectations

Follows requirements and meets all functionality. No bugs were present on localhost.


### Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application.


- Meets Expectations

Straightforward Readme with instructions to clone down and where to visit the live site


### HTML/UI

The team put some effort into styling, and the application is not confusing to use. HTML classes and IDs are kebab case.


- Above Expectations

Stlying is tip-top! All classes are kebab case.


### Accessibility

Developer implements code to increase accessibility.


- Meets Expectations

We have an alt for our delete button.

### JS syntax and Style

JavaScript code is logically divided into files. Developers can show examples of good coding practices and demonstrate OOP concepts, like DRY and separation of concerns. Developers pay attention to indentation and naming conventions. They also consistently utilize ES5 or ES6 syntax and jQuery when working with events.


- Meets Expectations

Divided into files logically but not as refactored as it should be. Indentation is tip-top also. ES versioning is a little all over the shop.

### Git Workflow

The team uses master for production, uses feature branches for small groups of cards, and has a pull request for each feature with good context and conversation. Developers that aren't on the team have commented on PRs.


- Below Expectations

Used a devlopment branch, but we did not utilize as many feature branches as we should have. No external developers commented on code.

### Project Management

The team is using a project management tool to keep their project organized and to track progress. Team is documenting conclusions and timelines on relevant cards.


- Meets Expectations

Used waffle and were consistent with submitting cards and communicating with one another.

### Communication

The team consistently reaches out to their Technical Lead for feedback on code quality and technical issues. The team responds to their Technical Lead in a timely manner.


- Meets Expectations

Did not reach out to technical lead but did not have a need to reach out and did not hear from the lead and so the 'responding in a timely manner' piece is not relevant.

-----------

## Instructor Rubric

### Evaluated By: Lauren

### Notes:

- Client README is solid. Wouldn't mind there being one for the API.
- Missing or buggy functionality:
  - Edit foods does not work and causes a browser alert
  - Add food from foods page does not work (making a GET request vs POST for some reason)
- AJAX requests are already async, so they don't need to be wrapped in Promises
- File division is strong, but many functions could still be refactored further
- server.js in Express API should be further refactored. That file should act more like a router, delegating action immediately to functions housed elsewhere (ideally a controller).
- Git workflow definitely needs work. API was built in 4 huge commits with 1 contributer, client has countless redundant commits that should be squashed
- Putting below expectations for Communication. I'd argue that there was need to reach out to TL for assistance, given the above notes.

### Specification Adherence

Application implements **all** functionality as defined, but some bugs or strange behavior where features intersect.

- **Below Expectations**

### Documentation

Developer provides easy to navigate documentation showing how to setup and contribute to the application.

- **Meets Expectations**

### HTML/UI

The team put some effort into styling, and the application is not confusing to use. HTML classes and IDs are kebab case.

- **Meets Expectations**

### Accessibility

Developer implements code to increase accessibility.

- **Meets Expectations**

### JS syntax and Style

JavaScript code is logically divided into files. Developers can show examples of good coding practices and demonstrate OOP concepts, like DRY and separation of concerns. Developers pay attention to indentation and naming conventions. They also consistently utilize ES5 or ES6 syntax and jQuery when working with events.

- **Meets Expectations**

### Git Workflow

The team uses master for production, uses feature branches for small groups of cards, and has a pull request for each feature with good context and conversation. Developers that aren't on the team have commented on PRs.

- **Below Expectations**

### Project Management

The team is using a project management tool to keep their project organized and to track progress. Team is documenting conclusions and timelines on relevant cards.

- **Meets Expectations**

### Communication

The team consistently reaches out to their Technical Lead for feedback on code quality and technical issues. The team responds to their Technical Lead in a timely manner.

- **Below Expectations**
