# Scale Up Submission Form - Open Source Projects

## Basics

### Links to the PRs or Issues You Picked Up

PR's I issued for work I did:   

[PR #82](https://github.com/LookingForMe/lookingForFrontEnd/pull/82)  
[PR #86](https://github.com/LookingForMe/lookingForFrontEnd/pull/86)  
[PR #89](https://github.com/LookingForMe/lookingForFrontEnd/pull/89)  
[PR #91](https://github.com/LookingForMe/lookingForFrontEnd/pull/91)  
[PR #92](https://github.com/LookingForMe/lookingForFrontEnd/pull/92)  

PR's I commented on:  

[PR #87](https://github.com/LookingForMe/lookingForFrontEnd/pull/87)  
[PR #88](https://github.com/LookingForMe/lookingForFrontEnd/pull/88)  
[PR #90](https://github.com/LookingForMe/lookingForFrontEnd/pull/90)    
[PR #94](https://github.com/LookingForMe/lookingForFrontEnd/pull/94)  


### Summarize what you worked on the last two weeks

For the past two weeks I worked on the LookingFor (Turing Legacy) project. My
goal from the outset was to gain as much exposure to React.js as possible. I
attended both classes on React. I completed another app in React, which was
based on a tutorial. And I worked on the project itself.

I fixed some issues we inherited related to tests and errors in the test suite.
I fixed issues with the configuration of ESLint. I implemented a feature that added
a favorites button to each job listing. Clicking the button would changes state
of that specific job and stores the job ID using localStorage.

Zack Forbing and I attempted to get a 'show favorites' feature implemented, but
found it more complex than we anticipated, and ran out of time. In retrospect, I
would have preferred to add 'favorites' as a column in the table in the database
and store that information there. Then we could have established an endpoint in
the API and made an Axios call from React to return a list of the favorites.
Additionally, we would have needed to implement authentication so that a user
could log in and save/see their favorites.

### Hours logged this week?

- Monday (0 hours):
- Tuesday (7 hours):
- Wednesday (7.75 hours):
- Thursday ( 5.25 hours):
- Saturday (2 hours):

### Talk about something from the pre-work that you didn't know about before this week.

I had no exposure to React, so when I first reviewed the existing code I was not
able to figure out the flow of data or what was happening. I have since learned
how React works and how the files are setup, configured and
connected. I particular I learned about 'props' - or the properties - that are passed
down and are accessible to the 'components'. React is relatively accessible for someone
with knowledge of JavaScript. Once you understand the file structure and the flow
of data, you can see how React is organized, readable and easy to follow.

### Link to blog post(s) submitted

[The Rise of React](https://gist.github.com/kbs5280/805929249c6ebc4952875dcd8bf2ed88)

### Discuss: your experience doing PR reviews and getting PR feedback

Reviewing PR's and giving feedback was a positive experience.

I am sometimes nervous about having my code reviewed. However, getting good
feedback is a great way to learn and write better code. It's not just the
specific advice, but learning how other developers might approach a problem, or
seeing a clearer syntax. I found that the comments were helpful, but also very
supportive and encouraging. Getting even one really positive line of feedback
is really encouraging, especially from more experienced developers.
[PR #89](https://github.com/LookingForMe/lookingForFrontEnd/pull/89)

I tried to comment on as many PR's as possible. I found it a little challenging
in that I am new to the language and framework and I did not have a lot to
contribute. I learned from the feedback I received what types of things to
look for and how to appropriately address those issues. This is the one area I
would have liked to have contributed more. And this is an area I need to work on.
[PR #87](https://github.com/LookingForMe/lookingForFrontEnd/pull/87)

### Discuss: your experience doing a blog and getting feedback (links are nice)

Writing the blog post was challenging. I chose to write a post on two pieces of
technology I was not familiar with. It took a lot of hours of research just to
understand the basics of each subject. Each subject had a number of complex
components, such as data binding, that I had to spend time understanding before
I could make any comparisons. Trying to compare something you don't understand to
something else you don't understanding can be tricky. I appreciated the challenge.
[The Rise of React](https://gist.github.com/kbs5280/805929249c6ebc4952875dcd8bf2ed88)

Getting feedback was really helpful. Some of the feedback was on the content,
some on grammar, and some on readability. It can be difficult to have
perspective on what you are writing when you have been immersed in it for hours
or days. Having objective feedback is essential. I was able to apply a lot of
changes and improvements based on the feedback I received.

### Discuss: your experience doing daily stand ups

Our stand ups were productive. Each team member took a couple of minutes to go over what they
were working on, planning to work on and any blockers. It was good practice. While
these stand ups were not essential to this project, it's easy to see how this would be a
very useful practive in the workplace. In an agile development environment, where plans can
change on a daily basis, it is important to communicate regularly.

### What features would you like to see the open source project you worked on have in the future?

I think the billing hours and self-directed approach should stay the same. I
think the legacy projects are not conducive to learning and they
shouldn't be used again. I would like to see specific paths for the Open Source
students, such as React or Ember. Each path would have optional classes and an associate
project spec. If there were brownfield projects for each path, they should be written by an
instructor and there should be intentional components to add and code to refactor,
so that students can get in and learn as much as quickly as possible.

### Please feel free to ask any other questions or make any other statements below!

-----

Instructor Evaluation:

__150 total points__

### Blog Post (40 Points)  

* __40: Developer has 500+ words across, one or two blog posts, about their independent study.__
* 25: Developer has posted blog(s), but fell short of 500 words.
* 0: Developer created no blog posts.

### Team Participation (50 points)

15 + 5 + 10 + 5 + 5 + 5 + 5 = 50

Points in this section are cumulative

* 15: Developer participated in 2 daily stand ups
* 5: Developer participated in a 3rd daily stand up and was able to speak to their work in a way that was clear and informative.
* 10: Developer submitted a detailed pull request for review
* 5: Developer provided useful feedback on a PR review request.
* 5: Developer provided useful feedback on a second PR review request.
* 5: Developer provided useful feedback on a blog post draft.
* 5: Developer provided useful feedback on a second blog post draft.

### Hourly Work (20 points)

* __20: Developer logged 21+ hours, or has a reasonable plan to do so over the weekend__
* 15: Developer logged 18 to 21 hours per working day, or has a reasonable plan to do so over the weekend
* 10: Developer logged < 18 hours
* 0: Developer did not track hours

##### Modifiers

Modifiers cannot take you below 0 points for the section

* -10 points: Developer is unable to speak to work completed

### Risk Taking and Creativity (40 points)

Instructor/Developer will select one feature in the project to review for this section of the rubric.

* __40: Developers pushed themselves and their team by taking risks which is demonstrated by a delivered feature or well documented spike. Developers explored concepts and technologies outside the scope of the curriculum.__
* 20: Developers pushed themselves and their team by taking risks which is demonstrated by an almost delivered feature whose next steps are not well documented.
* 10: Developers attempted to implement extensions using technologies not covered in class but it did not result in code or documentation.



__150__
