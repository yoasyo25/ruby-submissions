## Cloney Island Sprint 1 - Individual Evaluations

### Notes

### Client Expectations

Student delivered user story agreed upon with client.

- **4: Better than expected**
- 3: As expected
- 2: Below expectations
- 1: Well below expectations

### Test Quality

Story is well-tested (Above 90% and the most valuable pieces of the app are covered). If you were paying for someone to build this for you, would you be satisfied with the tests that are written?

- 4: Better than expected
- **3: As expected**
- 2: Below expectations
- 1: Well below expectations

### Code Quality

Project demonstrates well-factored code and a solid grasp of MVC principles.

- 4: Better than expected
- **3: As expected**
- 2: Below expectations
- 1: Well below expectations

Notes:

* Feed class is super clean and reads nicely.
* Wonder if we could refactor the `FollowsController`:

```
case params[:target_type]
when "Venue"
  target = Venue.find(params[:target_id])
when "Wine"
  target = Wine.find(params[:target_id])
when "User"
  target = User.find(params[:target_id])
end
```

to something like this:

```
params[:target_type].constantize.find(params[:target_id])
```

We'd need to account for the fact that someone might send over a `:target_type` that isn't legit.

* The logic in `Follow#report_follow` feels a little bit like it violates SRP. I might try to create a new object such as `FeedPreparer` or something like that. I don't feel super strongly about this but my gut says the `Follow` class knows a bit too much about `Feed`s and that at some point it could come back to bite us.

* Should have more tests at the unit level.

* Overall really solid just some small refactors. Nice Job!
