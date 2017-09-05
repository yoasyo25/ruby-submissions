### Project Template

### 3D Print Queue
### Pitch

An app that manages 3d Printer usage for maker spaces.

### Problem

The Denver Public Library ideaLAB and other library makerspaces currently use a number of forms, spreadsheets, cloud file storage accounts, paper sign ups, and various scripts to manage the waitlist for printing time on their public 3D printers. Their current solution works, but takes a lot of staff time and is prone to errors. In addition, no relevant statistics can be pulled easily from the current setup. 

### Solution

The 3D Print Queue app will accomplish all parts of the print queue system in a single app. It will allow frontline staff to help library patrons submit projects (and will automatically filter submission files for file type). It will then allow makerspace administrators to approve or reject projects, will allow projects to enter the queue based on pre-defined criteria (i.e. a patron can only have one job in the queue at a time). When a project is complete, the app will auto-email patrons. Ultimately, the app will report back statistics about 3D printer useage. 

### Target Audience

This app will be applicable to public makerspaces that offer 3D printing to customers. There is an immediate need in the public library community. The app will be used first by the Denver Public Library, but will be shared out to othr public libraries through the PLA and ALA communities.

### New Techniques

I intend to write the entire app in Javascript, with a Node/Express/Postgresql backend. I will need to learn to use Oauth through Dropbox in Javascript and understand and implement authentication and authorization with separate frontend and backend apps. I will need to learn to schedule automatic emails and use some chart library in Javascript to present statistics. Ultimately, I will also need to figure out how to schedule automatic deletions of old files in Dropbox.

### Workflow

I intend to use Waffle.io for project management.
