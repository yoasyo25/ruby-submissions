## Find Your City / FilmFinder

### Pitch

 - Prefice: I can't decide between 1 and 2.
  
  1) A one stop show to idenitify relevant fields important to individuals interested in moving to new cities. Research results presented from large scale fields.
  
  2) A movie reccomendation tool that compares a user's current/past history of rating films and uses that to compare across other movie review services. Once the connections has been done, the quantified 'priority' multiplier is used to sort through and reccomend a film personilzed to the user's taste.

### Problem

  1) Isn't it inconvienient keeping track of different categories of data when evaluating different cities/areas to live. There is a need for a one stop shop representation of different cities based on relevant information we want to know. Job opportunities accross industries, cost of living, relative safety, population, age, education rates, etc. 
  
  2) With the amount of review services out there for movies (and tv shows) do you use them to try to find a new movie suggestion? Do you prefer one service to the others? While I understand and agree with the idea of prioritizing the reviews from that site, you might be missing out on a great movie your favorite review site misses the ball on. Wouldn't it be nice if there was a product that consumed the reviews from multiple popular review services and compared them based on your own review(1-10) and reccomended future movies based on that behavior?

### Solution

  1) Data Science: I will build an app with will consume US Bureau of Labor, FBI Crime Data, and US Census Data (All 3 are reccomended for Data Science projects, so I feel comfortable these will return info I can work with) and then compare accross that data to give a visual representation of different cities OR build enpoints with search functionality so individual users can return n cities that fullfill their search data. 

  2) Machine Learning: I will hit the endpoints for Rotten Tomatoes, Fandango, Movie Database, etc. and store the results for a movie by title. I will make sure that any movie that a user selects as "seen" will have the exact format needed to compare across the other movie reviews from the API endpoints. The program would track the comparison between sites and begin to prioritize the review service(s) that the user is mostly in agreement with. It will then reccomend movies based on a similar "seen" film that the user gives as a reference point.

### Target Audience

  1) Kind of anyone. It depends I guess, if I go with the visual representation that will cast the net far wider because it will be easier to interact with. I guess a qualifier could be my target audience are the type of people that like to research an area they are interested in moving to/visiting. Realistically, it would probably skew towards the affluent. But I think that is the case with everything.

  2) My target audience for this are people utilize, preferably multiple, movie review services trying to find a good suggestion for a new movie. The users would need to be patient in recording their movies with their rating to compare across multiple services and reccomend movies based on your custom results. I could potentially build an "Express Reccomendation" Tool which is a quick 10 question "Rate the Movie" That cycles through the 100 most viewed movies ever. We would then use those 10 ratings to create our user baseline and compare and recommend. 

### New Techniques

Python (Consumption of big data + backend lang) 2. Django (To connect our app to a server and Host) 3. Frontend page dynamically updates with JS 4. Either R for statistal responisbilities or Angular if I have Python do all the math.  

### Workflow

What project management tool will you be using to manage your progress?
Probably just Waffle.io for this one. I don't want to pay for Jera and I would much rather just keep up a Waffle board for this one.
