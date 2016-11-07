# Scale Up Submission Form

## Basics

### Summarize the work you completed over the last two weeks
The past two weeks:

Non-Code Related:
  - Read Swift Docs
  - Completed an in-depth tutorial
  - Read Swift blog posts and tutorials
  - Attended ALL daily Stand Ups (plus a bonus Stand Up with Chris and Ryan).
  - Reviewed more than the required amount of PR's and Blog Posts each week.
  - Wrote a blog outline, draft, and published it on Medium.
  - Met with my Mentor on 11/2 for 2:00 hours.
  - Attended Advanced JS with Nate.
  - Attended Responsive CSS with Andrew.

Code Related:
  - I displayed hard-coded golf course names in my UITableView.
    - This was essentially wire framing and experimenting with my view in code.
  - Made a `GET` request to my EarlyBird API (specific course `courses/1`).
  - Parsed and appended course name to the array used in my UITableView.
  - Reloaded main thread (this allowed me to use my pulled data rather than hard-coded data).
  - Changed my endpoint from specific course to all courses.
    - `/courses/1` to `/courses`
  - Refactored business logic to a Course model.
  - Implemented a `for in` loop to append course objects to my courses array used in my UITableView.
  - Implemented open browser functionality when user taps a course
    - `UIApplication.shared.open()`
  - Modified my Mod 3 EarlyBird:
    - Views to accommodate mobile
    - Tee Times button is a Log In with Google button unless current_user.
  - App is fully functional from a user perspective :golf: :tada:
    - User can select a course and book a tee time.
    - Twilio text message is still sent to my phone, not the user's phone because I am on a trial Twilio account.

    ---
  ![EarlyBirdGif](http://recordit.co/Eqnb9BvRX8.gif)

### Link(s) to Your Work

[EarlyBird GitHub URL](https://github.com/matthewrpacker/EarlyBird)

### Hours logged this week?

- Monday (0 hours): N/A
- Tuesday (8 hours): 7:18 hours
- Wednesday (8 hours): 11:41 hours
- Thursday (8 hours): 8:05 hours
- Friday (0 hours): N/A
- Weekend (0 hours): 2:23 hours

### Talk about something that you didn't know about before this week.
Before beginning this, I didn't know how to:
- Write in Swift
- Use Xcode
- Consume and parse data from an API in Swift
- Display parsed data in a UITableView
- Open browser a browser with Swift

### Link to blog post(s)
[From Ruby to Swift](https://medium.com/@matthewrpacker/from-ruby-to-swift-cc2d02cff93d#.ws5a3zeql)

### Discuss: your experience doing PR reviews and getting PR feedback (links are nice)
I enjoyed the whole PR process.  Reviewing PR's gave me experience understanding a new code base and providing useful feedback.  Receiving feedback on my PR's was helpful because I was able to gain a second opinion on the readability of my code.

- [Submitted PR to add load data functionality to my UI](https://github.com/matthewrpacker/EarlyBird/pull/2)
- [Submitted PR for refactoring+](https://github.com/matthewrpacker/EarlyBird/pull/3)
- [Reviewed Zack's and Jenny's PR](https://github.com/LookingForMe/lookingForFrontEnd/pull/87)
- [Reviewed Ryan's PR](https://github.com/ryanflach/text_talk/pull/1)

### Discuss: your experience doing blog reviews and getting feedback (links are nice)
- [Reviewed Chris's blog post](https://medium.com/@chrisconcannon/second-steps-with-the-android-sdk-95d9336f5b29#.yw8kc8f9m)
- [Reviewed Ryan's blog post](https://medium.com/@ryanflach/723f71c4b4a2#.vg62evcoz)

### Discuss: your experience doing daily stand ups
Stand Ups added structure to my day.  I found it was helpful to reflect on what I accomplished yesterday, what I plan to accomplish today, and identifying an barriers that I have.  I really like structure and having a game plan.  Also, I enjoyed hearing about other people's progress.  I found this to be motivating.

### Please feel free to ask any other questions or make any other statements below!
I enjoyed the Stand Up project, but here is some feedback:
- I see the value of optional classes (provides students with a flexible schedule to look for jobs or work on what they view as most important), but I often felt conflicted whether I should attend class or work on my project.  Basically, I know there were some classes that I would have liked to attend, but I felt as though I needed to spend that time working on my project.
- I think Scale Up would be a terrific "post-Turing project".  For example, if students have not yet found a job, Scalue Up would provide instant structure, an opportunity to learn something "outside of the curriculum", and maintain the student network.  This may help student feel more connected while adjusting to life after Turing.
-----

# Instructor Evaluation:

Points: (max 150)

### Blog Post (40 Points)  

* 40: Developer has 500+ words across, one or two blog posts, about their independent study.
* 25: Developer has posted blog(s), but fell short of 500 words.
* 0: Developer created no blog posts.

### Team Participation (50 points)

Points in this section are cumulative

* 15: Developer participated in 2 daily stand ups
* 5: Developer participated in a 3rd daily stand up and was able to speak to their work in a way that was clear and informative.
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
