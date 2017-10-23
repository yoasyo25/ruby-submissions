### Project Template

### [Project Title]

### Pitch

1 sentence that explains the value proposition of the application. How would you explain it to a potential business partner, team member, or investor?
This application will provide a valuable service to algorithmic traders of cryptocurrencies by providing real-time data on cryptocurrency volatility.

### Problem

1-3 sentences describing the problem that you are trying to solve.
The only existing sources of cryptocurrency volatility data require the user to download a CSV to access the data. This approach is unsuitable for traders whose algorithms make real-time decisions and need a real-time data source.

### Solution

1-3 sentences describing how your application will solve that problem.
This application will provide a websocket stream of cryptocurrency volatility data. It will receive raw data by consuming an exchange's websocket stream, process that data to calculate the volatility, then output the volatility data via a websocket server.

### Target Audience

1-3 sentences describing what type of user your app would be applicable to.
This type of app would be useful for traders whose algorithms depend on cryptocurrency volatility data. 

### New Techniques

Which new techniques are you hoping to implement?
I am hoping to run this on a Node server, store past data in a Postgres database, and serve up calculations with websockets.

### Workflow

What project management tool will you be using to manage your progress?
I will use Waffle to manage my progress.
