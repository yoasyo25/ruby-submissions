# Student Name

**Add links to relevant code bases or production sites here:**

FrontEnd
https://github.com/bretfunk/anki_sound_frontend
https://bretfunk.github.io/anki_sound_frontend/

Backend
https://anki-sound-backend.herokuapp.com/
https://github.com/bretfunk/anki_sound_backend

---------------

Self Assessment Rubric
------------

_Please choose the score you think you've earned in each category below. Please also describe why you feel you've earned this score for each section!_

### 1. Project Planning & Management

*   4: Developer has a highly detailed iteration map, sophisticated organization in their tracker tool, and exceptional Git workflow
I used waffle.io and had both my frontend and backend on there as two seperate 'waffles'.  I also emailed Katelyn detailed reports of everything I was working on, stuck on, and remaining schedule.  

### 2. Completion & Pace

*   4: Developer delivers stories committed to before starting the sprint
I submitted user stories early on (not sure when the sprints actually started since everything was adjusted with QS).  For the most part, I was right on track, even though I had another project I had to do that had to be worked on at the same time (for a potential employer).  The only situation where I didn't complete and pace well was when I was stuck for two days on downloading.  That is something I am not happy about (though I tried everything I could think of!) and I def think that I could have done better somehow and it is something I will still have to fix before I feel comfortable putting this on my resume.  

### 3. Implementation Quality


*   3: Project exhibits tested (where applicable), maintainable, and well-organized code. Developer can speak to architecture Since this was two applications and was very frontend-heavy, I will give myself a three because although I used React best pracitices (or at least the ones I knew) someone who was actually trained in React would probably find ways to improve my code.  I personally did not like the React setup of putting everything in App.js and moving it down.  It seemed the opposite of MVC, which I like.  In fact, I intentionaly made a few components more MVC like in order to better troubleshoot and be closer to SRP.  I didn't do this much but I had a hard time troubleshooting backwards up the React chain and keeping everything in the App.js file had the code smell of hitting a surfeit of skunks with a flamethrower.  If I had to do it all over again I would use Redux, which I hear allows you to have the eqlivient of global variables and not have to keep everything in App.js and pass it all down.  That seems much closer to OOP.  I couldn't even pull out the AJAX calls in my app because they needed to talk to the variables in state.  It was annoying.

I also think I deserve a three and not a four because the downloading aspect of my program can be fickle, sometimes it works, sometimes it doesn't.  It isn't my code but the server I am getting the files from.  I think I should have figured that out even if Katelyn gave her blessing for me to move on and just do it the temporary way for now.  

### 4. Application of Techniques

*   4: Developer builds project in a new language(s) or framework(s)

Not only did I use React, my app was very frontend heavy so I did more React than most.  My backend was pretty sparse.  I also built seperate apps, which adds a lot of complexity (and errors!) and used the Knock gem to get the apps talking to each other securely.  

### 5. Documentation

*   4: Developer also adds a screencast, tutorial or other wow factor
- I don't know that it has much 'wow' but I made a Youtube tutorial: https://youtu.be/3ly823FDBK0
- It took about five takes for me to get audio at all but the quality isn't that great so I will redo it once I add the additional features.  

### 6. Accessibility

*   3: Developer implements code to increase accessibility
Since this is an audio application it is very possible that people will use it who have accesiblity issues.  For that reason, I made everything in buttons so they would be easier to use and made the colors very contrasting.  Before my project was scaled down somewhat, I was going to include the abiltity to listen to audio files without downloading them.  I had this feature working, I just didn't have enough time to implement it in a nice way.  It is something I will do before immediately after Turing so my program is more accessible to users.  

---------------


Instructor Assessment Rubric
------------

### Evaluated By: Katelyn

### Notes:

### 1. Project Planning & Management

*   4: Developer has a highly detailed iteration map, sophisticated organization in their tracker tool, and exceptional Git workflow

### 2. Completion & Pace

*   3: Developer plans stories ahead of sprint and makes some scope adjustments along the way

### 3. Implementation Quality

*   3: Project exhibits tested (where applicable), maintainable, and well-organized code. Developer can speak to architecture and implementation decisions

### 4. Application of Techniques

*   4: Developer builds project in a new language(s) or framework(s)

### 5. Documentation

*   4: Developer also adds a screencast, tutorial or other wow factor

### 6. Accessibility

*   3: Developer implements code to increase accessibility
