# Ellen Cooper

**Add links to relevant code bases or production sites here:**

* [Production]https://emcooper.github.io/coin-cluster-client/
* [Server-side App Repo](https://github.com/emcooper/coin-cluster)
* [Client-side App Repo](https://github.com/emcooper/coin-cluster-client)

---------------

Self Assessment Rubric
------------

_Please choose the score you think you've earned in each category below. Please also describe why you feel you've earned this score for each section!_

### 1. Project Planning & Management

*   4: Developer has a highly detailed iteration map, sophisticated organization in their tracker tool, and exceptional Git workflow
#### *   3: Developer uses an iteration map to plan project scope, breaks down broad features into granular tasks, and exercises good Git workflow (e.g., feature branches, descriptive commits, incremental PRs)
*   2: Developer has a mental vision for the project iterations, shows some use of a tracker tool, and uses Git effectively
*   1: Developer shows little evidence of project planning and management

I provided a simple iteration map, which I felt was detailed enough given the scope of this project. I used waffle effectively but not in a way that I would describe as sophisticated. My git workflow utilized branches and PRs, and my commits were adequately descriptive.

### 2. Completion & Pace

#### *   4: Developer delivers stories committed to before starting the sprint
*   3: Developer plans stories ahead of sprint and makes some scope adjustments along the way
*   2: Developer implements very little of the planned sprint
*   1: Developer does not plan or complete sprint

I delivered all of the functionality laid out in my iteration map and my user stories on waffle. 

### 3. Implementation Quality

#### *   4: Project demonstrates exceptionally well tested (where applicable) and maintainable code
      * for topics outside of BE curriculum, developer can speak to best practices applied
#### *   3: Project exhibits tested (where applicable), maintainable, and well-organized code. Developer can speak to architecture and implementation decisions
*   2: Project demonstrates some gaps in code quality and/or developers cannot defend their decisions
*   1: Project demonstrates poor factoring and/or understanding of general programming principles such as MVC and OOP

I included unit testing on the Node.js backend for all methods that were simple enough to test. I did not test the React app but I think that is outside the backend curriculum. I took pains to refactor the code to make it flexible and easy to change - for example, the frontend has no knowledge about the exchanges, I could delete or add an exchange on the backend and the tables and graphs would automatically adjust. I tried to do the same with the backend, refactoring the code so that if I were to add or delete an exchange api only a few changes would be needed. I tried to keep methods small and reusable. The exception to this is the chart component, because I decided to hand-roll a data smoothing algorithm for one of the markets. This was a complicated process and the code feels heavy, but despite the complexity I tried to keep the code as readable as possible. 

### 4. Application of Techniques

#### *   4: Developer builds project in a new language(s) or framework(s)
*   3: Developer implements four new techniques or patterns
*   2: Developer implements 3 or less major techniques that have not been previously attempted
*   1: Developer does not implement new techniques

I built this in Node.js and React, and used websockets for the first time. 

### 5. Documentation

*   4: Developer also adds a screencast, tutorial or other wow factor
#### *   3: Developer provides easy to navigate documentation showing how to setup and contribute to the application
*   2: Developer provides barebones documentation showing how to get the dev environment up and running
*   1: Developer provides insufficient documentation

My read me has setup and deployment instructions and an extensive contribution section.

### 6. Accessibility

*   4: Developer expertly implements features to follow accessibility best practices
#### *   3: Developer implements code to increase accessibility
*   2: Developer considers accessibility issues but has not yet produced code to address them
*   1: Developer does not consider accessibility issues

I read a lot about accessibility during the project and confirmed that much of my code was following these practices. I installed a tool called Axe that analyzes websites and pinpoints accessibility issues. I fixed the two issues that it found that were fixable (the other issues were related to Axe not being able to read the chart object). These issues were adding an aria label to the dropdown and changing the dropdown button to have a better color contrast ratio. There is definitely more I would have liked to add, to be at an 'expert' level, specifically making th dropdown accessible via tabbing. I researched this but could not find a clear explanation of how to do this easily, and felt if I went down that path of trying to figure it out it would have potentially cost me time that I needed in order to complete all of the features laid out in my iteration map. 

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
