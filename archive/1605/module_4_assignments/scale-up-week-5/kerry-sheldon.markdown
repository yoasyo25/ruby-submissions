# Scale Up Submission Form

## Basics

### Summarize the work you completed over the last two weeks

### Link(s) to Your Work

 - [Github Repo](https://github.com/kjs222/police_data)
 - [Production](https://sandiego-police-data.herokuapp.com)

### Hours logged this week?

- Monday (8 hours):     3
- Tuesday (0 hours):    9
- Wednesday (8 hours):  7.5
- Thursday (8 hours):   1.5
- Friday (0 hours):     2.5
- Weekend (0 hours):    8


### Talk about something that you didn't know about before this week.

I didn't know that Sequelize would produce different API results in production than development.  It's a good lesson that you can write a bunch of tests that pass in development and still not be building something that will work in real life.

I also learned a good lesson about not putting things in classes and ending up with things interfering with each other because of global variables.  I put code for two different charts in the same file because I didn't bring in any packages to let me require files for the client side code. I was getting really strange behavior when trying to update the legend on one chart because they shared a variable name.

### Link to blog post(s)
[Post](https://medium.com/@KerrySheldon/deploying-a-node-app-and-importing-a-postgres-database-to-heroku-8ad7bc9a2639#.3he48u4yz)

### Discuss: your experience doing PR reviews and getting PR feedback
I received feedback from an alumni on a PR that I posted this week.  It was super helpful.

I didn't really have an opportunity to review PRs this week. I just didn't see many/any that I knew anything about on the days that I was available to work on this project.

### Discuss: your experience doing daily stand ups

I participated in all of the scheduled daily stand ups this week.

### Please feel free to ask any other questions or make any other statements below!

-----

# Instructor Evaluation:

#### Notes

- Re: dev testing vs production execution: Staging servers are meant to deal with some of these issues. A full deployment flow often includes running tests in staging, and it's someone's responsibility to ensure that staging is configured the same way as Production. But yeah, sometimes stuff slips through the cracks.


Points: (max 150)

### Blog Post (40 Points)  

* **40: Developer has 500+ words across, one or two blog posts, about their independent study.**
* 25: Developer has posted blog(s), but fell short of 500 words.
* 0: Developer created no blog posts.

### Team Participation (50 points)

Points in this section are cumulative

* **15: Developer participated in 2 daily stand ups**
* **5: Developer participated in a 3rd daily stand up and was able to speak to their work in a way that was clear and informative.**
* **10: Developer submitted a detailed pull request for review**
* 5: Developer provided useful feedback on a PR review request.
* 5: Developer provided useful feedback on a second PR review request.
* 5: Developer provided useful feedback on a blog post draft.
* 5: Developer provided useful feedback on a second blog post draft.

### Hourly Work (20 points)

* **20: Developer logged 21+ hours, or has a reasonable plan to do so over the weekend**
* 15: Developer logged 18 to 21 hours per working day, or has a reasonable plan to do so over the weekend
* 10: Developer logged < 18 hours
* 0: Developer did not track hours

##### Modifiers

Modifiers cannot take you below 0 points for the section

* -10 points: Developer is unable to speak to work completed

### Risk Taking and Creativity (40 points)

Instructor/Developer will select one feature in the project to review for this section of the rubric.

* **40: Developers pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.**
* 20: Developers pushed themselves and their team by taking risks which is demonstrated by an almost delivered feature whose next steps are not well documented.
* 10: Developers attempted to implement extensions using technologies not covered in class but it did not result in code or documentation.
