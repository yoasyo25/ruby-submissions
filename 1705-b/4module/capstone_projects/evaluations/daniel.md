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

### Evaluated By: Lauren

### Notes:

- good use of fixtures in specs
- aws in the works

### 1. Project Planning & Management

*   **3: Developer uses an iteration map to plan project scope, breaks down broad features into granular tasks, and exercises good Git workflow (e.g., feature branches, descriptive commits, incremental PRs)**

### 2. Completion & Pace

*   **3: Developer plans stories ahead of sprint and makes some scope adjustments along the way**

### 3. Implementation Quality

*   **3: Project exhibits tested (where applicable), maintainable, and well-organized code. Developer can speak to architecture and implementation decisions**

### 4. Application of Techniques

*   **3: Developer implements four new techniques or patterns**

### 5. Documentation

*   **3: Developer provides easy to navigate documentation showing how to setup and contribute to the application**

### 6. Accessibility

*   **2: Developer considers accessibility issues but has not yet produced code to address them**
