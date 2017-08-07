## Cloney Island Sprint 1 - Individual Evaluations

### Notes

### Client Expectations

Student delivered user story agreed upon with client.

- 2: Below expectations

* Agreed upon 4 endpoints and only 1 was completed.

### Test Quality

Story is well-tested (Above 90% and the most valuable pieces of the app are covered). If you were paying for someone to build this for you, would you be satisfied with the tests that are written?

- 2: Below expectations

* Agreed upon 4 endpoints and only 1 was completed. A better way to use factory girl for associations would be to create the project backers with the pledge amount. So create 4 regular project backers and then for custom project backers, you can use factory girl like: `project_1 = create(:project_backer, pledge_amount: 8888)`. Right now, a lot of json is being displayed on the page but we are only checking for the title.

### Code Quality

Project demonstrates well-factored code and a solid grasp of MVC principles.

- 2: Below expectations

* Missing 3/4 endpoints that were agreed upon and no serializers to format json for the endpoint that existed. 
