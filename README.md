# Software Engineering 2 - PiSynthesis Project

This page displays the personal Log of Kristan Birbalsingh (816003409) of the events and thought as the production of the PiDronics System carries on.

# Kristan Birbalsingh
- 816003409
- gtatrinidad@hotmail.com
- Github Repo [(https://github.com/PiDronics)](https://github.com/PiDronics)

## Log

### September 4 2018
- Asked Qarun to join their group for SWE2, got acepted

### September 7 2018
- Discussed with the group to try and find a 5th person for the project, didn't get any

### September 19 2018
- Discussed project specifications
- Plan the member assignment and methods of collaboration for milestone 1

### September 20 2018
- I got a copy of the project details from Michael, which was a project the others did in SWE1. I used this to figure out the specifics of the project, what has to be done and what is already done

### September 23 2018
- Started discussing the idea of getting stakeholders from a contact Qarun got who is associated with the Ministry of Agriculture
- Everyone joined the Trello and Slack groups to start tracking progress

### September 25 2018
- Went to meet Kyle in the office in the morning but was not there
- Decided on Qarun being SCRUM master and Michael being Product owner
- Finalized on the milestone 1 details for submission the next morning

### September 26 2018 to October 1 2018
- I didn't get to do any work regarding this project
- I was focusing on other assignments, things at home, DVR security system setups, port forwarding and helping some of my year 2 CompSci friends with preparations for their courseworks.

### October 2 2018
- Started back work on the project. It was a bit fun to start back doing some prototype development and preparing tasks for milestone 2.

### October 3 2018
- Went back to finish off some other assignments
- I was also taking breaks by watching the Instant Regret Click this Playlist playlist on youtube (I had started it some unknown date ago). I was aiming to finish all 2500+ videos soon

### October 4 2018
- I downloaded Webstorm as the preferred editor for the development of the project which was recommended by Qarun.
- Installed it and realsied that there are too many dependencies I'd have to install on Windows, so I went ahead to install an Ubuntu VM and use Webstorm on that. (The reason I had to reinstall those things is because I wiped my computer during the holidays)

### October 7 2018
- Had a Hangouts call with the team to discuss upcoming tasks.
- I showed the others of the Firebase DB layout I have for my CodeJam project which would've been similar to how this project's Firebase DB would become to give them an idea of how the data flow would be for the Pi devs and App devs of the project.

### October 8 2018
- Started gathering default content to use in the prototype for the front end design.
- I started and finished a functional prototype for the front end using HTML, CSS and some JS (no libraries and frameworks because it was just for screenshot and element purposes)
- I realised that I found myself searching for "how to" for different simple JS and CSS things which I've done before but had to re-learn but I guess it would help when actually developing the application. (Future note: I never used it...)

### October 10 2018
- The git repo was made and I started work by making an individual branch for the feature I was to do for that iteration.
- Again, I found myself searching for "how to" on different git command things that I should have already remembered after so many times I did it (but I guess I forgot since I didn't do any recently).
- I checked Trello for tasks and Slack for some communication with the others on how to begin.
- A Firebase DB was created but no one was added yet but I didn't let that stop me. I made my own DB to start using for development until I got added. I created a JSON template of the data and started filling it with test data.
- I didn't bother with authentication just yet as I wanted the data to be written and read to the proper places first.
- I also started some basic React tutorials and some of which included integration with Firebase.
- The rest of this day was just a bunch of learning on React, how it works, etc.
- By the end of the day, I was impressed by how easy React is and how smooth it works that I've planned on replacing Django as my main form of web development (although I'll miss the easy SQL backend capabilities of Django but I'll find a suitable replacement to work with React eventually)
- Gave myself a treat with Wintergatan's new video released today.

### October 11 2018
- Did a bit of Firebase data filtering for the app and was basically just learning how to use React better and understanding the workflow more.

### October 12 2018
- I made this GitHub page today and started filling it with log details. I got a bit tired with it and left it in an incomplete state (until 30th October).
- I checked out material.io which Qarun recommended as the UI library for the app and started testing it out on this interation.

### October 13 2018 to October 15 2018
- Started working on some Python assignments I had for another course.
- Also helped a friend with the designing of a 3D skeleton they had to make for their nephew's PE class.
- Didn't get anything done towards this project today.

### October 15 2018
- Had a meeting with everyone to decide the new product owner and scrum master. Also discussed the new iteration a bit and agreed on an improved front end design. Confirmed the database structure and planned for the next physical meeting.
- Started following up on some more tutorials in React and Redux in accordance to Firebase (see playlists here)
[Link 1](https://www.youtube.com/playlist?list=PL4cUxeGkcC9iWstfXntcj8f-dFZ4UtlN3)
[Link 2](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBbSLZjvleMwldX8jGgXV6a)

### October 16 2018
- For the new iteration tasks and requirements, I didn't like the amount of work required to use material.io in React (it wasn't a lot but it could've been less) so for the new iteration front end deisgn, I did some research and found MDBootstrap which had a React component version as well so I designed the version 2 (see project's git branches) of the app using this UI library instead.
- Learnt how to use React's public folder and just kept on working on the increment.

### October 17 2018 to October 19 2018
- This new version of the front end app was to implement "multiple pages" (it's a single-page app) and using the mdbootstrap components made the presentation of content on each "page" much cleaner.
- I had to modify the structure of the Firebase DB into a more suitable form that the app would benefit from.
- I learnt a bit about CircleCI which Qarun was to set up into the project to understand how it works and how I should write my code in compatibility for testing.
- I kept working on the app for this period and started to feel as if I'm putting in a lot more effort than I should because I was getting exhausted and this was the only work I was doing for any course, putting in about 10-15hrs of the day into the app (because I enjoyed it and I don't like to leave things unfinished). I thought that I'm most likely putting in more effort into this project than compared to what I think the others are doing. I speculated this thought as realised it's most likely because my work is visual and apparent whereas I can't see the work Michael and Gabby are doing on the Pis and Qarun is doing on setting up tests and testing integration and they're also organising things with stakeholders. I also thought that if my idea on that is wrong, I wouldn't mind doing more to make the stress on them a bit easier because they do have other work to deal with as well.

### October 20 2018
- Different graph/chart libraries were discussed and evaluated for the purpose of presenting data to the user.
- Initially, Highcharts was chosen.
- I started some research on conditional rendering in React and how to set up loading animations then realised that isn't a priority and went back to creating and generating the required components.
- Created the placements required for the graph and the relevant titles, etc.
- When I was about to install and equip Highcharts in the project, I started reading on it more and realised Highcharts is free for non-commercial use and started looking for free commercial alternatives.
- I brought up Chart.js, Google Charts and ChartKick as alternatives to the group for evaluation. Chartkick took the chicken dinner because it's basically a middle man for chart.js and Google Charts which had support for React by providing chart components which then created the charts using an underlying library (chart.js or Google Charts).

### October 21 2018 to October 24 2018
- Started applying the graphs to the project
- I started to implement Firebase authentication into the app as well with conditional rendering depending on if the user is signed in, etc.
- I learnt how to do redirects in React that wouldn't refresh the browser page.
- I started to experience some bottlenecks in development that would've been due to minimalistic way I went about learning React where states and rendering were starting to get problematic.
- I decided to take a break from all school work for a day or 2 because I haven't done anything for myself in a while as well as my head was cluttered with code and I wanted a clean slate to start back work to. I watched some Boruto, recorded some CSGO and Ring of Elysium gameplay to make videos from to put on my gaming channel [Here's the channel if you're interested](https://youtube.com/user/KCBGamingVideos)

### October 25 2018 - October 28 2018
- I did not do any new tasks for the start of the iteration because I was occupied with other work, however in my spare time I did do some research how to do data transfer between child TO parent components (parent TO child is easy to do), and sibling components. I needed to do this for the graphs and the related forms for choosing the range of data for the graph.

### October 29 2018
- I adjusted the firebase database authentication rules by adding indexing rules to the sensor data so that the data would be filtered and sorted by the time value when being pulled from the database.
- I also made the components for the form needed to manipulate the range of data to be pulled for the graph. The form comprised of start and end dates, and hours, minutes and period for the start and end time.

### October 30 2018
- Today I just finished tweaking the conversion of dates to form values and form values to dates and then committed everything to Github.

### October 31 2018
- The team had a SCRUM meeting today where I was appointed the new SCRUM master. We discussed what was pertinent for completion at this state and I made a soft lust of these things. At this point, we were mainly concerned with getting the remaining hardware we needed and confirming a deployment for the system.

### November 1 2018
- I didn't get to do anything today related to the project.

### November 2 2018
- I started creating the tasks for this iteration (4) on Trello and assigning the specific members to handle it. I realised that the Trello for iteration 3 didn't have fully explained tasks so there was a bit of confusion in some aspects so I tried to resolve that for iteration 4.

### November 3 2018 to November 6 2018
- I didn't do anything because I was a bit preoccupied with other assignments.

### November 7 2018
- I added a small fix to the site's navbar where selecting an item from the dropdown menu on mobile would close the menu. Before it would've stayed open.

### November 13 2018
- Today I designed how I thought the Configuration page should look, by drawing it on MS Paint. I then sent the images to the group asking for their opinion on whether it's missing anything or the layout should change. They accepted the design so I started implementing the design.
- I first modified the test data on firebase to add test data for the configuration page to utilize and modified the authentication rules for said data. The rules there was basically a user can only view and modify their own systems and not any authenticated user's data (which it was by default before).

### November 14 2018
- Development of the Configuration page still went on today. I did get stuck on a bug where I couldn't update some data in the database because of a bad line in te authentication rules. I resolved it and continued with the work.

### November 15 2018 - November 16 2018
- I completed the creation of the UI elements for the Configuration page and had a successful connection to the database for reading and writing data.
- With the completion of this final page for the site at this iteration, I modified the database rules to prevent all unauthorised actions. By default (for development purposes), the "write" rules had no constraints meaning unauthorised users and authorised users had access to write to any part of the system. During development, I was mainly concerned with "read" rules only.

### November 17 2018 - November 18 2018
- I didn't do any work today. Decided to take a break and compose some music on FL Studio. If you're interested in it, let me know, I'll send it. (The title is Dark Storm).

### November 19 2018
- Qarun had done a push of his work yesterday where he was doing testing, and code minimalization but he made an error where the values for the Sensor table did not load so I went ahead and fixed that. The issue was the wrong database location the data was trying to be gathered from.

### November 20 2018 - November 21 2018
- I did not do any work during these days related to the project but I was doing some research on SQL databases with Javascript and implementation of it on React. I did this for my own knowledge because Django is the only SQL web framework I know and I started to like React so I wanted to know how to implement SQL in React. I didn't learn any of it yet but I have the links saved for express.js and tutorials on routing, etc.

### November 22 2018
- Another bug I discovered from Qarun's code was that the form for configuring the graph's data did not load with any initial values. This was because he accidentally left them commented out so I fixed that.

### November 23 2018 - November 24 2018
- I did not work directly related to the project but I was researching Firebase's Admin SDK to see if it would've been of any use to the project. It turned out that we had no use for it as of now.

### November 25 2018
- Since I was finished with the site's main components, I decided to go through the entire front-end system's code and implement all possible try-catch statements and return promises where available to display more well-defined errors and improve some rendering.
- There was also some extra code in some of the files I was going through that was commented out and was obsolute so I removed those as well.
















