### Feature Delivery

**1. Completion**

* 1: Project fails more than 7 (10 for individual project) spec harness tests.

_The project is failing 27 tests from the spec harness._

### Technical Quality

**1. Test-Driven Development**

* 4: Project demonstrates high test coverage (>90%) and tests at the controller and unit levels.

_Test coverage is at 90.95%_

**2. Code Quality**

* 2: Project demonstrates some gaps in code quality and/or application of MVC principles.

_There's too much logic still living in a few controllers. For example, the `random` inputs have the controller implementing the logic rather than extracting this out to the model level._

**3. API Design**

* 3: Project uses strong and consistent data formats throughout, while relying mostly on standard Rails JSON features.

**4. Queries**

* 2: Project has some gaps in ActiveRecord usage, including numerous business methods that rely on ruby enumerables to find the appropriate data.

_The relationships leverage ActiveRecord associations, but there are no business intelligence methods_
