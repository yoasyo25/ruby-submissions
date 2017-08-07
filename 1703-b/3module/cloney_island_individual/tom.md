## Cloney Island Sprint 1 - Individual Evaluations

### Notes

### Client Expectations

Student delivered user story agreed upon with client.

- 4: Better than expected
- 3: As expected
- **2: Below expectations**
- 1: Well below expectations

### Test Quality

Story is well-tested (Above 90% and the most valuable pieces of the app are covered). If you were paying for someone to build this for you, would you be satisfied with the tests that are written?

- 4: Better than expected
- 3: As expected
- **2: Below expectations**
- 1: Well below expectations

Notes: Pretty solid unit tests for reviews. When testing an API in RSpec you should create a `requests` directory and do the POSTing from their. By placing your spec in that directory RSpec will know you are writing a request spec and give you access to methods like `get` and `post` instead of `visit` which is what you get in a feature spec.

### Code Quality

Project demonstrates well-factored code and a solid grasp of MVC principles.

- 4: Better than expected
- **3: As expected**
- 2: Below expectations
- 1: Well below expectations

Notes: Looks like you were attempting to set up a `new` action in the API. APIs don't need `new` or `edit` since that's the page that forms are displayed. Instead, you should set up a `create` action that will receive POST requests.
