# Ideabox 2.0 Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/revenge_of_idea_box.markdown)

# Basics

### Link to the Github Repository for the Project
[GitHub](https://github.com/matthewecampbell/idea_box)

### Link to the Deployed Application
[Heroku](http://mattsideabox.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Commits](https://github.com/matthewecampbell/idea_box/commits/master)

### Provide a Screenshot of your Application
[Screenshot](http://imgur.com/a/30ODf)

## Completion

### Were you able to complete the base functionality?
* Yes.

### Which extensions, if any, did you complete?
* Sorting based on quality.  I started tags but gave up.

### Jiff of my extension working.
* [Jiff of sorting](https://imgflip.com/gif/1by3k7)

# Code Quality

### Link to a specific block 'good' code on Github
* [Update Idea function in ideas.js](https://github.com/matthewecampbell/idea_box/blob/master/app/assets/javascripts/ideas.js#L120-L133)
  * This was a particularly challenging part of the project for me - especially because I had never heard of "text-editable" before.  On top of that I was able to learn about different events you could use including on 'blur' which was fun for me to discover.

### Link to a specific block of 'bad' code on Github
* [Sort function in ideas.js](https://github.com/matthewecampbell/idea_box/blob/master/app/assets/javascripts/ideas.js#L178-L192)
  * This was 3am and I had pneumonia and just wanted to get it to work.  The if statements make it seem a bit janky.

### Test Suite Status
```
...................

Finished in 0.70606 seconds (files took 3.04 seconds to load)
19 examples, 0 failures

Coverage report generated for RSpec to /Users/matthewcampbell/Desktop/turing/module_4/idea_box/coverage. 41 / 41 LOC (100.0%) covered.
```

### Link to an example of a test that covers an 'edge case' or 'unhappy path'
* I don't believe I have one.

###Please feel free to ask any other questions or make any other statements below!
* I think I did pretty well on this project.  My tests are certainly not as robust as I would like, but I had a lot of things outside of normal Turing life going on outside of this project.  I do feel as though I have a much better handle on JavaScript than I did 5 days ago.


## Instructor Evaluation Points

103 +


* 1 for not accounting for truncated text

* Clearing the search box should restore all the ideas to the list. (1 points)

#### Sorting

(10 additional points.)

When viewing the ideas list, the user should have the option to sort ideas by Quality. The default sort should be descending ("genius" → "plausible" → "swill"), and clicking the sort a second time should reverse it. The Idea list should be sorted client-side without reloading the page.

## Instructor Evaluation Points

### Specification Adherence

* **10 points**: The application consists of one page with all of the major functionality being provided by jQuery. There is no use of `format.js` in Rails. There is no use of unobstrusive JavaScript. There are no front-end frameworks used in the application. No approach was taken that is counter to the spirit of the project and its learning goals. There are no features missing from above that make the application feel incomplete or hard to use.

### User Interface

* **3 points** - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

### Testing
* 6 - One feature test testing that the root path existed.

* **8 points** - Project has a running test suite that tests and multiple levels but fails to cover some features. All controller actions are covered by tests. The application makes some use of integration testing.
* **5 points** - Project has sporadic use of tests and multiple levels. Not all controller actions are tested. There are little or no attempts at integration testing.

### Ruby and Rails Quality

* **8 points** - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

### JavaScript Style

* 7 - Some minor bugs - one duplicated function to refactor - small refactor opportunitites - I like the use of promises

* **8 points** - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing.
* **5 points** - Your application has some duplication and minor bugs. Developer can speak to most choices made in the code and knows what every line is doing.

### Workflow

* **10 points** - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
