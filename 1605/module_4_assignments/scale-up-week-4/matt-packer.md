# Scale Up Submission Form (Check In) Instructions

- [Project Spec: Whiskey Tango](https://github.com/turingschool/lesson_plans/blob/master/ruby_04-apis_and_scalability/independent_study_project.markdown)

# Student Feedback

### Blog draft

- [Blog Post Outline for 500+ word Post](https://docs.google.com/document/d/1JLBqsfGJbRQBBQ-CYwuJVTNt3mDDNytktm6qtDDaF1k/edit?usp=sharing)

### Hours

Document your general hours below (or planned hours)
- All hours have been documented on Harvest
- Pre-Work (1 to 3 hours): 3 hours
- Monday (8 hours): 9 hours
- Tuesday (8 hours): 7:52 hours
- Wednesday (8 hours): 9:19 hours
- Thursday (8 hours): PLANNED ~7:00 hours (completed 2:25 hours as of Noon)
- Weekend (0 hours): PLANNED (~8:00 hours / TBD)

### Participation

Speak to your participation in PRs (links would be nice), blog reviews and in your project groups.
- Participated in Stand Up on Monday, Tuesday, Wednesday, Thursday (Ryan-initiated).  I Plan on participating in Stand Up on Friday (Ryan-initiated).
- [Reviewed Ryan Flach's PR for setting up Firebase](https://github.com/ryanflach/good-morning-sunshine/pull/1) and provided feedback on GitHub.
- [Reviewed Caleb Cowen's PR for basic styling refactor](https://github.com/Caleb9193/brotha-nature/pull/1) and provided feedback on GitHub.
- [Reviewed Ryan Flach's blog post draft](https://medium.com/@ryanflach/ff7e5256ce86#.5fe12hd0c) and sent him a DM with my feedback.
- [Reviewed Chris Concannon's blog post](https://medium.com/@chrisconcannon/getting-started-with-the-android-sdk-11d18fcd7ae4#.g6cyhaxli) and sent him a DM with my feedback.
- [Reviewed David Tinianow's blog outline](https://docs.google.com/document/d/1jkNHOt1GHbrqkZbdKbGYQI4IJD9LA2pPcoghj5fFeAE/edit?usp=sharing) and sent him a DM with my feedback.
- [Reviewed Jason Hannah's blog outline](https://medium.com/@TheJasonHanna/b20872ba5aa1#.qsdkolakd) and sent him a DM with my feedback.
- [Submitted First Swift PR](https://github.com/matthewrpacker/EarlyBird/pull/1) and shared the link in PR-rodeo channel.
- [Responded to feedback on my PR from Ryan, David, and Matt C.](https://github.com/matthewrpacker/EarlyBird/pull/1)
- I completed a [Blog Post Outline for 500+ word Post](https://docs.google.com/document/d/1JLBqsfGJbRQBBQ-CYwuJVTNt3mDDNytktm6qtDDaF1k/edit?usp=sharing) and shared the link in the PR-rodeo channel.  Both Lane and Ryan provided feedback via DM.
- I did my best to be active in the PR-rodeo channel.

### Work Completed

Link to and describe the code/research you have completed so far.

##### Reading / Research / Tutorials / Code

- [A Swift Tour](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/GuidedTour.html#//apple_ref/doc/uid/TP40014097-CH2-ID1)
  - Read through A Swift Tour Docs and tried using the some of the syntax in their REPL: To begin `$ swift`, to exit `$ :quit` or `$ :exit`, or `$ :q`. Also, I researched swift tutorials that I could utilize during the week (per suggestion from Andrew Carmer).
- [UI User Interface Catalog](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/UIKitUICatalog/index.html#//apple_ref/doc/uid/TP40012857-UIView-SW1)
  - Read through the UIKit User Interface Catalog (all portions of Views and Controls).
- [View Controller Programming Guide for iOS](https://developer.apple.com/library/content/featuredarticles/ViewControllerPGforiPhoneOS/index.html#//apple_ref/doc/uid/TP40007457-CH2-SW1)
  - Read through View Controller Programming Guide for iOS up to "View Controller Definition Implementing a Container View Controller".
- [Team Treehouse](https://teamtreehouse.com/tracks/ios-development-with-swift-20)
  - Completed their "Network Programming with Swift 2" tutorial.  I didn't link to that tutorial specifically because you need an account to access it.  Free 7-day account if you are interested.
- [Alamofire](https://github.com/Alamofire/Alamofire)
  - Alamofire is a "cocoa pod", basically a swift version of a Ruby Gem.  After reading through their docs, I decided to pursue the purist approach with NSURLSession (built-in Apple API for downloading content). FYI, prefix of NS in NSURLSession is no longer required in Swift 3.
- [Simple REST API Calls With Swift](https://grokswift.com/simple-rest-with-swift/)
  - I walked through this blog / tutorial.  I tried implementing some of the logic in my project to access a specific golf course route on my API: https://early-bird-courses.herokuapp.com/api/v1/courses/1.  I liked this blog / tutorial because it did not rely on any third-party providers (e.g. cocoa pods, similar to gems). I found that being able to just write code was more helpful/enjoyable than installing / setting up third-party dependencies in Xcode.
- [First Swift PR](https://github.com/matthewrpacker/EarlyBird/pull/1)
  - I implemented some basic networking code from the blog / tutorial mentioned above.  My implementation only handles a `GET` request at the moment.  I was able to print my `GET` request to the Xcode console with the `course["name"]`, which was "Overland Park". At the time, this felt like a huge success.
  - I replied to feedback on my PR from Ryan, David, and Matt C..
- I e-mailed a connection from Andrew Carmer. He has a friend that is currently developing in Swift that may be available to assist me, or point me in the direction of some helpful resources.  I received a response Wednesday evening.
- I signed up for [Medium](https://medium.com/)
- I completed a [Blog Post Outline for 500+ word Post](https://docs.google.com/document/d/1JLBqsfGJbRQBBQ-CYwuJVTNt3mDDNytktm6qtDDaF1k/edit?usp=sharing) and shared the link in the PR-rodeo channel.  Both Lane and Ryan provided feedback via DM.
- I did my best to complete this Submission form.

# Instructor feedback

### Week 4

/150 points

### Blog Post Draft (25 Points)  

* 25: Developer has **draft/outlines** for 2 small blog posts (~250 words) or one in depth blog post (500+ words) about what they have worked on for their independent study. Outline is reasonably in depth and shows research/thoughtfulness.
* 15: Developer has **a draft/outline** for a blog post.
* 0: Developer created no blog draft.

### Team Participation (50 points total)

Points in this section are cumulative

* 15: Developer participated in 4 daily stand ups
* 5: Developer participated in a 5th daily stand up and was able to speak to their work in a way that was clear and informative.
* 10: Developer submitted a detailed pull request for review
* 5: Developer provided useful feedback on a PR review request.
* 5: Developer provided useful feedback on a second PR review request.
* 5: Developer provided useful feedback on a blog post draft.
* 5: Developer provided useful feedback on a second blog post draft.

### Hourly Work (25 points)

* 25: Developer logged 28 to 34 hours, or has a reasonable plan to do so over the weekend
* 20: Developer logged 24 to 28 hours per working day, or has a reasonable plan to do so over the weekend
* 15: Developer logged < 24 hours
* 0: Developer did not track hours

##### Modifiers

Modifiers cannot take you below 0 points for the section

* -10 points: Developer is unable to speak to work completed


### Risk Taking and Creativity (50 points)

Instructor/Developer will select one feature in the project to review for this section of the rubric.

* 50: Developers pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.
* 30: Developers pushed themselves and their team by taking risks which is demonstrated by an almost delivered feature whose next steps are not well documented.
* 10: Developers attempted to implement extensions using technologies not covered in class but it did not result in code or documentation.
