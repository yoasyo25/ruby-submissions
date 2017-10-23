### Project Template


### [Risa For The People]
** https://www.risaforthepeople.com/

### Pitch

This project aims to create for the Risa White for Senate District 32 program that will automatically take, filter, and upload form data from her campaign website, to a centralized, private political database called VAN for her campaign's future use.

### Problem

In the opening throes of a senate race, nearly everything needs to happen all at once and on a limited budget. While her campaign could benefit from a variety of app constructs, we've decided that the most pressing issue to tackle is that of updating her website to a state-senate-worthy status, which above all needs a way of storing survey and form data. Additionally, her campaign depends on data from a privately authorized server called VAN, and so we'd like to figure out a way to synthesize and combine the two sets of data into one location for her campaigns analysis and use.

### Solution

We are thinking about first converting her from SquareSpace to Wordpress, and updating the HTML/CSS/front-end side of her website to a polished, professional look that accentuates Risa's dedication to her constituents, as those that I've talked to have all warned against coupling any application with SquareSpace. Secondly, I will build a background worker that will sync with her website, and automatically convert form data to a CSV. Finally, we will take that CSV and upload the data to VAN either using the same background worker or in a separate async process.

### Target Audience

My application will be usable for any campaign that wishes to update their own constituent data on the private voter-data software program NPG VAN[https://en.wikipedia.org/wiki/NGP_VAN]. Having a program that automatically fast-tracks the time-consuming process of converting and uploading website form-data will greatly benefit any campaign looking to streamline their internal process and free up their limited volunteer base to do more critical actions / other work. The application holds the potential to include future data-analysis features as well.

### New Techniques

I have never built a background worker, a queue system, or SideKiq/Foreman. I plan to be constructing it as a Rails app, predominantly in Ruby I'm sure, and will use Sidekiq as my background processing library.

### Workflow

I will be using Waffle.io and GitHub to manage my work, and will be communicating with the campaign via Slack, email, and cellphone.
