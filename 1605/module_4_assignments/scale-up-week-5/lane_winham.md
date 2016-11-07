# Scale Up Submission Form - Open Source Projects

## Basics

### Link(s) to the PRs or Issues You Picked Up
[PR Reviewed](https://github.com/LookingForMe/lookingForFrontEnd/pull/88)

[PR Reviewed](https://github.com/LookingForMe/lookingForFrontEnd/pull/87)

[PR Opened](https://github.com/LookingForMe/lookingForFrontEnd/pull/93)

### Summarize what you worked on the last two weeks

During the last two weeks, I worked on researching/learning React and finding ways to contribute using those learned skills. First, I wanted to alter the RD3 chart on the trends page. I wanted to change it into a pie chart or something that was easier, in my opinion, to see percentages. This process was not as easy as I would have assumed because the data being returned by the axios call was not conducive to other chart formats. I also looked at how to better sanitize data being displayed on the main job's list page. I found that certain jobs were still being rendered even if they were outside of the 9 languages being searched for. I implemented some flow control to fix this issue but decided to remove them in order to not override another functionality that was proposed at a stand-up. The last aspect I worked on was paired with Jason. We tried to implement a "refer a friend" feature that would allow a user to enter an email and click send. When clicking send, an axios post request would be sent to the backend app with all of the job details and email address to send it to. I believe Jason and I have everything in place but are having issues with the axios request. Testing the endpoint with postman works and using a debugger to check the params being sent also returns what we expect but the request never hits the backend controller action.

### Hours logged this week?

- Monday (0 hours):
- Tuesday (5 hours):
- Wednesday (7 hours):
- Thursday (3 hours):
- Friday (3 hours):
- Saturday (0 hours):
- Sunday (4 hours):

### Talk about something from the pre-work that you didn't know about before this week.

How to manage and pass state from parent to child was made a great deal more clear during this week.

### Link to blog post(s) submitted

[Medium Post](https://medium.com/@mlwinham12/from-ruby-on-rails-to-react-7679638fbb2d#.2ks814o0k)

[Blog Post Review](https://gist.github.com/kbs5280/805929249c6ebc4952875dcd8bf2ed88)

[Blog Post Review](https://medium.com/@calebcowen/the-bright-and-scary-world-of-frontend-3640b1bcbbe#.711wz7o1s)

### Discuss: your experience doing PR reviews and getting PR feedback

I thoroughly enjoyed this aspect of the project. I think it makes you think about what your planning to do in greater detail and what it would bring to the app as a whole. I also liked being able to look at others code and go line by line examining what was happening. This is extremely helpful when learning a new library.

* I think this should be part of the curriculum in other modules

### Discuss: your experience doing daily stand ups

I liked doing daily stand-ups as well. It allows everyone to be on the same page first and foremost but also acts as tool for keeping all accountable.

### What features would you like to see the open source project you worked on have in the future?

I think it would be great to pull all of the styling out and let others create styling from scratch. I also think that the scope of only 9 languages should be increased to encompass the front and backend.

### Please feel free to ask any other questions or make any other statements below!

-----

Instructor Evaluation:

150 total points

### Blog Post (40 Points)  

* 40: Developer has 500+ words across, one or two blog posts, about their independent study.
* 25: Developer has posted blog(s), but fell short of 500 words.
* 0: Developer created no blog posts.

### Team Participation (50 points)

Points in this section are cumulative

* 15: Developer participated in 4 daily stand ups
* 5: Developer participated in a 5th daily stand up and was able to speak to their work in a way that was clear and informative.
* 10: Developer submitted a detailed pull request for review
* 5: Developer provided useful feedback on a PR review request.
* 5: Developer provided useful feedback on a second PR review request.
* 5: Developer provided useful feedback on a blog post draft.
* 5: Developer provided useful feedback on a second blog post draft.

### Hourly Work (20 points)

* 20: Developer logged 21+ hours, or has a reasonable plan to do so over the weekend
* 15: Developer logged 18 to 21 hours per working day, or has a reasonable plan to do so over the weekend
* 10: Developer logged < 18 hours
* 0: Developer did not track hours

##### Modifiers

Modifiers cannot take you below 0 points for the section

* -10 points: Developer is unable to speak to work completed

### Risk Taking and Creativity (40 points)

Instructor/Developer will select one feature in the project to review for this section of the rubric.

* 40: Developers pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.
* 20: Developers pushed themselves and their team by taking risks which is demonstrated by an almost delivered feature whose next steps are not well documented.
* 10: Developers attempted to implement extensions using technologies not covered in class but it did not result in code or documentation.
