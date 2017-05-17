## Sinatra versus Rails Exploration

### Setup:

First, clone down the Rails project:

```terminal
git clone https://github.com/turingschool/job-tracker.git rails_project
```

And then clone down the Sinatra project:

```terminal
git clone https://github.com/turingschool/bike-share.git sinatra_project
```
Now cd into each project, run `bundle` on each project, and you're ready to go. We will only be looking at the code base and not interacting with the app. If you wanted to run the server and interact with the app, you would need to create your database, migrate your migrations, etc.

### Exercise:

1. Take a look at this stripped down Sinatra app and this stripped down Rails app. How are they different and how are they similar? Identify 5 differences, and for each one describe 1-2 implications. What effect does that difference have for each framework? If you don't know exactly, draw on your knowledge and experience and make some educated guesses/inferences. Also, practice your research skills to look into the differences.

>The first diffence I notice when comparing the Sinatra and Rails apps is that their are a lot more directories in the rails app.  Both apps share the directories "app", "config", "db" and "spec" but but the rails app also has the additional directories "bin", "lib", "log", "public", and "vendor".  Within the "app" directory in the Rails app there are also a few more subdirectories than in the Sinatra app.  Another difference that I notices is that within the "view" directory in the Rails app the view files are named with the convention filename.html.erb whereas in the Sinatra app they just had the ".erb" suffix.  In the rails there is a routes.rb that seems to handle the urls while the controller file handles CRUD functionality.

2. Consulting blogs and commentary you find online, identify 3 similarities between Rails and Sinatra.

>Rails and Sinatra are both ruby frameworks for creating web-apps.  Beyond that, it seems like everyone on the internet prefers to discuss their differences rather than their similiarities.

3. Consulting blogs and commentary you find online, identify 3 things that distinguish Rails, advantages.

>Rails provides a stronger framework for starting a new webapp project.  This helps maintain consistency across different Rails apps.  Sinatra provides less initial structure and leaves more up to the developer to design themselves.  From my reading it seems as though Rails is better at interacting with databases and creates more secure apps right out of the box while Sinatra may have the advantage in communicating with API's.

4. In your Rails project, what does the `routes.rb` file inside of the `/config` directory do? What does this correlate to in our Sinatra app?

>The routes.rb file inside the `\config` directory tells the cooresponding controller file to react with the correct method when a an http request is received.

5. We teach Sinatra by adding some structures that Sinatra doesn’t need, but help you make the transition between Sinatra and Rails. What does a stripped down implementation of Sinatra look like, and what are the pieces we’ve added for educational purposes?

The only major difference that I notice is that a stripped down implementation of Sinatra is not set up to work with databases. ????