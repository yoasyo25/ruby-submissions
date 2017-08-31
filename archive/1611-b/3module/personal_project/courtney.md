### Will Legislate for Money
#### Pitch
This project shows the data for politicians votes side-by-side with their campaign contributions in an effort to increase transparency.
#### Problem
Corruption in our government is at an all time high, or it at least appears to be because of the Information Age. By using voting and campaign data for senators, representatives, and other policy makers, citizens can be empowered to make changes in the candidates they support.
#### Solution
Use OpenSecrets API for campaign data with GovTrack.us API for voting data and create a show page for senators/representatives or other relevant officials. Users can view them by region and save a public official to 'follow'.
#### Target Audience
Citizens of US who are interested in having a one-stop-shop corruption watch.
#### Integrations
OAuth: Twitter or Google

APIs: OpenSecrets, GovTrack.us, Sunlight, World Bank Data, NYT & Other News APIs

### Iterations
#### One (Basic API Serving Data)
Guest users can view campaign donatoin data for a senator from their show page and view a link to a show page for contributors. Major contributor's show page includes a list of politicians they've sponsored and how much they've given.
A senator/representative or other politician's show page includes their basic information (name, image, state, term information, political party, etc.), their major campaign contributors, how to contact them, and how they've voted in recent decisions.
#### Two (OAuth + Search)
Users can OAuth in with Twitter or Google and enter their geographic information, probably zipcode since that works well with Sunlight API. Their state senators and representatives are automatically added to their "followed" politicians and they can see links to view their followed politicians from their show page. They can choose to follow other politicians. The benefit of following a politician is having an easy link to view their information from your dashboard. Users can view bill/legislation show pages from the politician show page or by searching key words / categories.
#### Three (Activity Feed)
Users can "follow" a bill or piece of public policy. This gives them a link to view all of the current information and adds it to their activity feed. Users have options to add news stories related to followed entities to their feed.
User dashboard includes recent activity from all followed entities (politician campaign info, how politicians have voted, recent news stories relating to politician or followed legislation). Could potentially add recent tweets from politician to their show page.
#### Four (Data Analysis is Cool)
**(not sure how this is going to work yet, consulting data scientists and mentors this weekend)**

Politicians receive a corruption-index score that looks at how they voted for a piece of legislation/policy, if/to what extent that policy benefited their campaign contributors (through World Bank Data stock prices maybe?), and if/to what extent that policy affected their constituents (recent polls / scraping news sources). I also might use some data scientists' models for corruption-perception-index to calculate the perceived corruption of a politician.

### Data Strategy
#### Automation
I plan to set up a background worker or something similar to download all of the information I need from these APIs and update it daily and use an internal API for that I consume. I want to do this to make the data analysis easier later since it isn't really an on-the-fly calculation for corruption indexing. I wonder if it would make sense to have a stand-alone API and make the app as a companion to consume the API. This would help with staying in the free-zone for production.


# Evaluation

You’ll be graded on each of the criteria below with a score of (1) well below expectations, (2) below expectations, (3) as expected, (4) better than expected.

## Feature Delivery

### 1. Completion

4: Developer completed all the user stories and requirements set by the client in timely manner.

### 2. Organization

3: Developer used a project management tool to keep their project organized.

## Technical Quality

### 1. Test-Driven Development

3: Project shows adequate testing (90% - 95% coverage).

### 2. Code Quality

4: Project demonstrates exceptionally well factored code.

## Product Experience

### 1. User Experience

3: Project exhibits a production-ready user experience.

### 2. Performance

4: Project pages load on average under 300 milliseconds.
