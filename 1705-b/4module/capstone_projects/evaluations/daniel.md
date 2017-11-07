# Student Name

**Add links to relevant code bases or production sites here:**

* https://github.com/thedanielvogelsang/VanCSVUploader
* https://van-csv-uploader.herokuapp.com/

---------------

Self Assessment Rubric
------------

_Please choose the score you think you've earned in each category below. Please also describe why you feel you've earned this score for each section!_

### 1. Project Planning & Management

*   3: Developer uses an iteration map to plan project scope, breaks down broad features into granular tasks, and exercises good Git workflow (e.g., feature branches, descriptive commits, incremental PRs)

I think I did a great job at maintaining focus, working continually throughout the sprint while pacing the correct things, and strategizing appropriately. The strategy of tackling backend before the API / front-end stuff was figured out was a very smart move. Thanks Lauren!

### 2. Completion & Pace

*   2: Developer implements very little of the planned sprint

I was able to build a beautiful front-end with React.
In part of this, I was also able to create a dropzone for drag-and-drop functionality.

I was able to move her website from SquareSpace to WordPress. We then converted her previous and boring form to this one[https://risaforthepeople.com/volunteer/] and install the plugin that allowed for quick and easy CSV file exportation.

I was able to successfully create an email and utilize new tools Redis and Sidekiq.

Despite my hard work, two major things are still keeping my project from reaching completion:

(A) Taking an app from development to production in VAN is a lengthier process than I anticipated. Because VAN handles nation-wide census and political data, posts cannot come from unauthorized sources. I am still awaiting official clearance to be able to make successful survey posts to the VAN /canvassResponses endpoint. As soon as i have that, I think my app will be ready for my candidate to use. I will be continuing to work with my candidate, and on her campaign website, here:

https://risaforthepeople.com/

(B) Although not specified in my proposal, I think currently my app is pretty un-usable to the public, as it is specifically synced with my campaign's survey data. Future iterations might include an admin dash, or an ability to change survey expectations for the CSV parser.

### 3. Implementation Quality

*   3: Project exhibits tested (where applicable), maintainable, and well-organized code. Developer can speak to architecture and implementation decisions

Many of my tests for the backend required sensitive data not appropriate for github. I have a larger test suite on my local computer, and used tests to almost exclusively TDD my backend. More tests to come once i get that api key.

### 4. Application of Techniques

*   2: Developer implements 3 or less major techniques that have not been previously attempted

### 5. Documentation

*   3: Developer provides easy to navigate documentation showing how to setup and contribute to the application

### 6. Accessibility

*   2: Developer considers accessibility issues but has not yet produced code to address them

My site is simple and easy to navigate. Once on the upload page, there is an additional click-and-submit button for those unable to drag and drop.

---------------
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

