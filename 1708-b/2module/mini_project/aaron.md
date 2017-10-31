### Project Option 3: PointBox

- Notes: might want to add some flash messages for errors. Cannot log out. Visually, needs a little work. 

Create an app where an admin (let's say for example, Richard) can assign points to users and users can redeem those points for rewards. Host your app live on Heroku.

#### Points

* [X] Points can be created ("assigned to a user") and destroyed only by the admin.
* [X] Points can be destroyed only by the admin.
* [X] Users can see their total number of points on their dashboard

#### Rewards

* [X] Rewards can be created, edited, updated, and destroyed only by the admin.
* [X] Rewards can be edited only by the admin.
* [X] Rewards can be updated only by the admin.
* [X] Rewards can be destroyed only by the admin.
* [X] The list of possible rewards can be seen by regular users.

#### Redeeming Points

* [X] Users can redeem their points for a reward.
* [X] When users redeem their points, the points are NOT destroyed; instead, they are marked as "redeemed".
* [X] when a user redeems points for a reward, the user can see that reward on their dashboard.

#### Authentication and Authorization

* [X] Users need to log in to see their points and rewards.
* [X] Users can only see their own points and rewards -- they should not be able to visit another user's page.
* [X] Users cannot add points to their account.
* [X] Users cannot create new rewards to add to the list.
* [X] A user cannot redeem another user's points.
* [] Admin can create a user.
