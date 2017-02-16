# Census

## Sprint 2 Closing Review

In the second half of Sprint 2 I see the key gains as:

* continuing to refine Census itself (functionality, workflow)
* added Yearbook as a sample application using Census as a data source/service
* finishing the bulk email inviting of users
* beginning to integrate with other teams' projects through offering an API

Some pieces that should have made it into this sprint but are uncompleted include:

* moving email to a worker (practicing services)
* implement live update on the invites page (practicing web sockets)
* integrate Gravatar

Some of these were features designed in response to the team's request to practice learnings from their class sessions, so it seems there's a missed opportunity for "Application of Techniques."

As we move into the last sprint our MUST DELIVER items are:

* App must be in production ASAP
* Review/audit the security and permissions practices/implementation
* Confirm that Enroll and Monocle can get the data to/from Census that they need to be up in production
* Put a rudimentary level of polish into the UI to increase user confidence

The team also needs to put an emphasis on applying their academic learning including:

* JavaScript in the UI (jquery, etc)
* Websockets for live updating
* Further usage of a message queue or pub/sub architecture
* Implement and validate the API gem

## Rubric Scoring

### 1. Project Management

* 3: Team is using a project management tool to keep their project organized.

PM tool is well used by the team but could use better interaction from the product owner.

### 2. Completion & Pace

* 3: Team is on track to complete all the user stories and requirements set by the client in timely manner.

Team delivered an adequate quantity of work during the period but could have prioritized a little better / delivered a few more cards.

### 3. Implementation Quality

* 3: Project demonstrates solid code quality and MVC principles.

Project shows a good distribution of work, many small commits, and decent branching/merging practices.

### 4. Application of Techniques

* 1: Project has a plan to implement a technique from academic classes.

Disappointed that the `/app/assets/javascripts` folder hasn't seen a commit in 23 days and we don't have any workers/async pieces.
