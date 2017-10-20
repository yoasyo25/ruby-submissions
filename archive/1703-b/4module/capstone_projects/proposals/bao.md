### Project Template

### Daily Fantasy Sports Lineup Generator

### Pitch

Daily fantasy sports allows you to go head to head with others in fantasy matchups which require you to select a lineup
that is under the salary cap. My generator will build your lineup for you.

### Problem

1. Building a lineup is really guesswork. We have intuitions about who will play well and who doesn't, but using statistics, we can build better lineups that will win greater than 56% of our matches.
2. Daily Fantasy Sports have salary caps. We have to build our team and be under the cap. It would be impossible for a person to generate trillions of possible lineups with the salary cap, but a computer could do that and find the best possible lineup. Of course even a computer generating these lineups will be slow. Another problem here to solve is to have the computer recurse through the lineup and generate the lineups faster. This will allow me to dynamically make changes to the lineup positions or salary cap, and have a lineup generated within milliseconds.
3. The app needs to notify you if the lineup has changed due to last second changes in weather forcasts and injury reports.

### Solution

1-3 sentences describing how your application will solve that problem.

My app will gather historical data for the past three seasons to generate estimated point production for this season. I will then import in this weeks "salary" data and then generate the best possible lineup. I will also get weather data because football is played in most weather conditions, and I will get injury reports to modify the player's point production. Lastly, I will build a single page app to serve this information up.

### Target Audience

Target audience are people who play daily fantasy sports. There is a lot of money involved and the idea is to help you win > 56% of matches that you enter in the $1 || $3 || $5 leagues. The idea is that the user would enter at least 10-20 matches (though ideally perhaps more than 100) and the user would win enough matches to make their money back.

### New Techniques

Building a single page app in React which will serve up all of my requests from a Rails API. The React app also may handle the lineup generation rather than the server.

### Workflow

I am using waffle.io to track my user stories.
