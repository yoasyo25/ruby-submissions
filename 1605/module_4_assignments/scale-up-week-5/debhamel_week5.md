# Scale Up Submission Form

## Basics

### Summarize the work you completed over the last two weeks
 * Read/review Leaflet.js documentation
 * Completed tutorial on Leaflet and rails
 * Read and review various blog posts and tutorials on building maps with Leaflet
 * Read documentation on React
 * Read and review various blog posts and tutorials on React
 * Built out React test app react-test
 * Built out Jeopardy React app and customizes data elements jeopardy
 * Built out React app to work with a Rails API data endpoint food_demo
 * Attended ALL daily Stand ups
 * Reviewed and commented on PR for Pahlka Posse project.
 * Wrote a blog outline, drafted and pivoted to new blog published on Medium.
 * Reviewed 4 blog posts and gave feedback.
 * Attended all classes
 * Volunteered to teach kids to code


### Link(s) to Your Work

[food_demo_react](https://github.com/deborahleehamel/food_demo_react)

[react-test](https://github.com/deborahleehamel/react-test)

[jeopardy](https://github.com/deborahleehamel/jeopardy)

[PR for React spike](https://github.com/deborahleehamel/food_demo_react/pull/1/files)

[Reviewed and added comments to Pahlka Posse PR from Tommasina](https://github.com/Turing-Pahlka-Posse/lunch_bunch/pull/2)



### Hours logged this week?

- Monday (0 hours):
- Tuesday (8 hours):
- Wednesday (8 hours):
- Thursday (8 hours):
- Friday (1.5 hours):
- Weekend (0 hours):


### Talk about something that you didn't know about before this week.
Firebase

How to get "create-react-app" to work with your Rails API and some specific tricks used in my spike project:

* add `gem 'foreman', '~> 0.82.0'` to enable booting both servers with one command

* touch `Procfile` in top directory to declare two processes: one for `web` (our React app) and one for `api` (our Rails server):

  ```
  web: cd client && npm start

  api: bundle exec rails s -p 3001
  ```
* boot Foreman command with `foreman start -p 3000`

* to simplify, create Rake task to execute this task in `lib/tasks/start.rake`

  ```
   task :start do

    exec 'foreman start -p 3000'

  end
    ```
* set up proxy for API server:
  ```
  // Inside client/package.json
  "proxy": "http://localhost:3001/",
```

* `Client.js` contained a Fetch call to the API endpoint and this was the one touchpoint between the React web app and the API server:

  ```
  function search(query) {
    return fetch(`/api/food?q=${query}`, {
      accept: 'application/json',
  }).then(checkStatus)
      .then(parseJSON);
  }
  ```


### Link to blog post(s)

[React.js, Getting to know you](https://medium.com/@deborahleehamel/react-js-getting-to-know-you-1df3b9a0cbe8#.aymkus4ym)



### Discuss: your experience doing PR reviews and getting PR feedback
It was really interesting to read other peoples PRs, but often I did not feel I had enough context or understanding of the projects to give feedback.

I think I gained some unique new perspectives on PR content and their value. Before scale-up, I had used PR requests mainly as a workflow tool for team repo management. Leaning on an established workflow for PRs that requires teammates to review pull-requests was a key component to keeping everyone on the same page with common awareness when multiple people work on the same code base. Often code review was about catching specific code edits or refactor suggestions before merging code into a code base.
During scale-up, reading over other folks PRs was illuminating. Consciously considering how to best to present information or comments in PRs led me to a new understanding of an expanded value for PRs. Pull requests can be places to add suggestions without specific code additions. It can also be a place to just ask questions about how something works or why a person chose to do something a particular way and create a space for a dialogue or discussion. Additionally, a well-crafted pull request can be used to document several elements and strategies that were involved in a particular set of code, a single feature or even a learning spike that has been implemented.


[Reviewed and gave suggestion to Matt on his blog post](https://medium.com/@matthewrpacker/from-ruby-to-swift-cc2d02cff93d#.q4ik0fsuu)

[Reviewed and gave suggestion to Zack on his blog post](https://medium.com/@zackforbing/where-to-begin-with-lookingfor-202803ecf1b0#.5sjvym73k)


### Discuss: your experience doing daily stand ups
This structured/reflective practice every day was invaluable. The exercise to express what you worked on the previous day, what you are working on today and any blockers always gave me this little boost of momentum to refocus on the day's immediate goals or address how to get past any blockers. Just knowing that you also will be doing a stand up creates an organizing principle for your thoughts at the end of each day for what you will report and talk about the next day in stand up. Hearing other people talk about their progress or blockers was awesome. We can gain incites from other's successes or offer incites to blockers and generally empathize with each other's feelings about productivity.

### Please feel free to ask any other questions or make any other statements below!

On scale-up: I know some felt it might have been better to have another round of structured project learning with JavaScript, React or another framework in Mod 4, but honestly, I truly valued the opportunity to start getting into an independent study mindset that we can and will need to transition to after next week. This got my wheels turning about how to stay proactive with planning each day with coding goals and deliberate practice and strategic communication with others. I think this gave me a good round of practice on how I can make a plan for self-learning and project work after next week. Really grateful for this time to experiment and self-organize.

-----

# Instructor Evaluation:

Points: (max 150)

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
