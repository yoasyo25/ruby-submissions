### BrokenFreedom: What's the Relationship between International Economic Liberty and Corruption

### Pitch
This open source project seeks to serve the international policy community by taking two popular datasets, the Economic Freedom Index and the Corruption Perception Index, synthesizing their data and making it more accessible through an API and a user interface.

### Problem
What is the relationship between economic freedom and perceived corruption in countries around the world? How do we make this data more accessible to both policy researchers and the average person?

### Solution
This application will make a combined dataset of the Corruption Perception Index and the Economic Freedom Index, layered over with key development indicators from the World Bank.

Users will be able to query and view this data through the application. The goal is to create an MVP website that demonstrates the potential of an API and interface to synthesize and make the data available to others.

The hope is that interest in the project and accessibility of the tech (Ruby / Rails) will enable collaboration for building this functionality in the future to address specific research questions.  

### Target Audience
This is geared to members of the international policy community and engaged world citizens who care about both corruption and economic freedom.

### Integrations

* Which APIs will you use?
The World Bank API. Potentially the Google Maps API for rendering on a map.

* Which OAuth integration are you planning to use?
Google.

### Iterations

1. Set up a Rails application and import both datasets into the database for years 2016 - 2013 (the years that both datasets overlap), selecting specifically two statistics for comparison between countries: the Economic Freedom Score and the CPI score. Render a table in the view combining this data.
2. Create API endpoints to expose this data using queries that can be called by country. Develop a simple statistical query that ranks these countries according to basic correlation between the two scores - countries with high economic freedom and low corruption index and vice versa.
3. Consume the World Bank API and add in a new layer of data using their World Development Indicators. Possibilities for interesting comparisons include central government debt as a percentage of GDP (code: GC.DOD.TOTL.GD.ZS), employment, electric power generation per capita, total alcohol consumption per capita, and bribery incidence (IC.FRM.BRIB.ZS). Serve this data combined with existing data via an API and render it into a table on the view.
4. Implement OAuth sign in for Google.
5. Display the data on a Google map that allows users to click to see the statistics for each country.
6. Use D3.js or another visualization library to visualize the data for the user.


# Evaluation

You’ll be graded on each of the criteria below with a score of (1) well below expectations, (2) below expectations, (3) as expected, (4) better than expected.

## Feature Delivery

### 1. Completion

3: Developer completed all the user stories and requirements set by the client.

### 2. Organization

3: Developer used a project management tool to keep their project organized.

## Technical Quality

### 1. Test-Driven Development

4: Project shows exceptional use of testing at different layers (above 95% coverage).

### 2. Code Quality

3: Project demonstrates solid code quality and MVC principles.

## Product Experience

### 1. User Experience

3: Project exhibits a production-ready user experience.

### 2. Performance

4: Project pages load on average under 300 milliseconds.
