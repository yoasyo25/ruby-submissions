# Matt DeVoe

**Add links to relevant code bases or production sites here:**

* Back-end Production (Rails API) - insight-api.herokuapp.com
* Back-end GitHub - https://github.com/mdevoe12/fitbit-backend
* Front-end Production (React) - https://mdevoe12.github.io/fitbit-front-end-react/
* Front-end GitHub - https://github.com/mdevoe12/fitbit-front-end-react
* Pivotal Tracker - https://www.pivotaltracker.com/n/projects/2123623


---------------

Self Assessment Rubric
------------

_Please choose the score you think you've earned in each category below. Please also describe why you feel you've earned this score for each section!_

### 1. Project Planning & Management

* 3 - Used pivotal to the best of my ability to break down iterations, steps, sub-tasks, labels, bugs and chores. This helped me stay organized and as on-schedule as possible. Additionally, I attempted to adhere to strict Github practices as much as possible. However, I did let features/chores/bugs bleed from one checkout branch to another.

*   4: Developer has a highly detailed iteration map, sophisticated organization in their tracker tool, and exceptional Git workflow
*   3: Developer uses an iteration map to plan project scope, breaks down broad features into granular tasks, and exercises good Git workflow (e.g., feature branches, descriptive commits, incremental PRs)
*   2: Developer has a mental vision for the project iterations, shows some use of a tracker tool, and uses Git effectively
*   1: Developer shows little evidence of project planning and management

### 2. Completion & Pace

* 3 - I did plan stories ahead of the sprints. Scope adjustments did have to be made on the fly as unexpected issues and events did occur.

*   4: Developer delivers stories committed to before starting the sprint
*   3: Developer plans stories ahead of sprint and makes some scope adjustments along the way
*   2: Developer implements very little of the planned sprint
*   1: Developer does not plan or complete sprint

### 3. Implementation Quality

* 3
* Rails: ~70% test coverage. Unit tests covered the majority of my code with some integration tests. I ran into challenging situations in attempting to perform a full integration test due to the nature of the split OAuth setup, FitBit's implementation of their OAuth/APIs. Unfortunately, mocking/stubbing/VCR/WebMock were a struggle with this particular setup. Additionally, I refactored as much as possible, attempted to use presenters, refactored services, pushing logic down to model levels and kept the code clean and organized.

* React: This being my first real dealing with React, I'm happy with how much I learned and my code quality. Components were broken down accordingly, conditional rendering is used regarding login/logout, props and state used and passed up and down the tree. Additionally, splitting OAuth between React and Rails proved challenging. First because I was lost in React, then due to one of the dependent npm packages not minifying upon npm build. As a result, I had to manually the first part of the OAuth handshake so as to get the app to deployment.

*   4: Project demonstrates exceptionally well tested (where applicable) and maintainable code
      * for topics outside of BE curriculum, developer can speak to best practices applied
*   3: Project exhibits tested (where applicable), maintainable, and well-organized code. Developer can speak to architecture and implementation decisions
*   2: Project demonstrates some gaps in code quality and/or developers cannot defend their decisions
*   1: Project demonstrates poor factoring and/or understanding of general programming principles such as MVC and OOP

### 4. Application of Techniques

* 3: I dove headfirst into a handful of new techniques and challenges for this project.
* a: Front end is built entireley in React (which I'm now loving).
* b: Figuring out how to split OAuth between two separate apps.
* c: Handrolling a token verification system between the Rails API and React for API calls and login/logout status.
* d: For the front-end, I decided, for the first time at Turing, not to use bootstrap to style. I did use the bootstrap column setup to help organize parts of the app. However, I decided to use JSX and CSS to deliver the page I wanted to see (drawing on inspiration from other website designs that I enjoy).

*   4: Developer builds project in a new language(s) or framework(s)
*   3: Developer implements four new techniques or patterns
*   2: Developer implements 3 or less major techniques that have not been previously attempted
*   1: Developer does not implement new techniques

### 5. Documentation

* 2 - 3: While my documentation isn't the most robust. I did spend a good amount of time attempting to walk potential contributers through setup and use of the two applications.

*   4: Developer also adds a screencast, tutorial or other wow factor
*   3: Developer provides easy to navigate documentation showing how to setup and contribute to the application
*   2: Developer provides barebones documentation showing how to get the dev environment up and running
*   1: Developer provides insufficient documentation

### 6. Accessibility

* 3 - I attempted to kill a few birds with one stone. I tried for a simple, but decently designed front-end for a number of reasons. I didn't want to overly complicate what should, in practice, be a straightforward, but enjoyable user experience. My goal for the minimal design was to keep the important information front and center. For those who may have attention or learning disabilities, this allows for an easier user experience. Additionally, I tried to use colors for background (black), text (white) and graph (white, yellow, turquoise) that contrasted well together. This allows for (hopeful) better readability for the general user and those who have color blindness. I used a chrome extension to analyze my page, I believe that 7 of the 9 types of presented color blindess were still able to interpret the charts. The only down side is that the legend that appears makes it difficult to read the details. I spent several hours trying to update the color schemes for the legend, unfortunately it's difficult with recharts. I may move to another charting library in the future.

*   4: Developer expertly implements features to follow accessibility best practices
*   3: Developer implements code to increase accessibility
*   2: Developer considers accessibility issues but has not yet produced code to address them
*   1: Developer does not consider accessibility issues

---------------


Instructor Assessment Rubric
------------

### Evaluated By:

### Notes:

### 1. Project Planning & Management

*   4: Developer has a highly detailed iteration map, sophisticated organization in their tracker tool, and exceptional Git workflow
*   3: Developer uses an iteration map to plan project scope, breaks down broad features into granular tasks, and exercises good Git workflow (e.g., feature branches, descriptive commits, incremental PRs)
*   2: Developer has a mental vision for the project iterations, shows some use of a tracker tool, and uses Git effectively
*   1: Developer shows little evidence of project planning and management

### 2. Completion & Pace

*   4: Developer delivers stories committed to before starting the sprint
*   3: Developer plans stories ahead of sprint and makes some scope adjustments along the way
*   2: Developer implements very little of the planned sprint
*   1: Developer does not plan or complete sprint

### 3. Implementation Quality

*   4: Project demonstrates exceptionally well tested (where applicable) and maintainable code
      * for topics outside of BE curriculum, developer can speak to best practices applied
*   3: Project exhibits tested (where applicable), maintainable, and well-organized code. Developer can speak to architecture and implementation decisions
*   2: Project demonstrates some gaps in code quality and/or developers cannot defend their decisions
*   1: Project demonstrates poor factoring and/or understanding of general programming principles such as MVC and OOP

### 4. Application of Techniques

*   4: Developer builds project in a new language(s) or framework(s)
*   3: Developer implements four new techniques or patterns
*   2: Developer implements 3 or less major techniques that have not been previously attempted
*   1: Developer does not implement new techniques

### 5. Documentation

*   4: Developer also adds a screencast, tutorial or other wow factor
*   3: Developer provides easy to navigate documentation showing how to setup and contribute to the application
*   2: Developer provides barebones documentation showing how to get the dev environment up and running
*   1: Developer provides insufficient documentation

### 6. Accessibility

*   4: Developer expertly implements features to follow accessibility best practices
*   3: Developer implements code to increase accessibility
*   2: Developer considers accessibility issues but has not yet produced code to address them
*   1: Developer does not consider accessibility issues
