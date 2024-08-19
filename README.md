# Hello there!

## <-- I'm Squall

Welcome!

I'm a lifelong lover of video games, recently relocated to the Austin area, in search of new opportunity and adventures.

As a part of that ambition, I took a web development bootcamp in 2021 with Hack Reactor, toward my goal of becoming a career developer. Unfortunately it seems my timing was not fantastic and the job search has thus far proven rather fruitless. But that hasn't stopped me yet!

Most recently I've slowed down a bit and (given the state of things) have decided to pursue more of what I'm curious about, than trying to chase what I think might improve my job prospects. Something I've found to be a horrible motivation and the projects I've done to that end are a joke. (See anything titled "portfolio")

PS- I'm on a campaign to get devs to change "Hello World"s to "Hello There"s. If you get the reference, join the rebellion!

## ​🇵​rojects

### [Tactical Chess](https://mythrilshield.itch.io/tactical-chess)♟
##### Strategy-driven Chess variant on Itch.io
###### [Github Repo](https://github.com/tspr0tege/Tactical-Chess)

The game is a project I concocted to learn the Godot game engine and gdscript language. The idea was to come up with something that would use at least some mechanic that would be applicable to a Tactical RPG, which is the ultimate goal. And it has been an interesting experience! I honestly never realized how complicated Pawns' movement rules were, until I had to explain it to a computer.

It's hosted on Itch.io and playable from the link above (click the header). It's only available as a locally playable game so far, and has all the mechanics I was hoping to implement. Though it does lack anything looking for check. On the upside, I accidentally made it work on mobile while trying to solve a different problem, so that was a happy surprise!

### [Quest Log](https://www.quest-log.app)📔
##### Gamified Task Manager
###### [Github Repo](https://github.com/tspr0tege/quest-log)

This project is currently hosted on AWS, and is running on: NGinx, PostgreSQL, Node.js/Express.js, React, and MUI, with authentication being handled through Auth0.
You can check the full list of dependencies in the [package.json](https://github.com/tspr0tege/quest-log/blob/main/package.json)

Everything in this project has been done from the ground up (no auto-builders like create-react-app), as I wanted to get exposure to the documentation and learn about these systems from a more fundamental level.

I most recently converted the project over to Material-ui, since I struggle most with design (and admittedly still need help).

Some project highlights:

Front-end:
- [QuestLog.jsx](https://github.com/tspr0tege/quest-log/blob/main/client/src/pages/MainApp/QuestLog/QuestLog.jsx): the main task-list component, and probably the most robust single jsx available on the project.
- [QuestsData.jsx](https://github.com/tspr0tege/quest-log/blob/main/client/src/components/QuestsData.jsx): a reuseable component I created to provide consistent access to API calls, and any mutations of the state data. 
- [API/quests.js](https://github.com/tspr0tege/quest-log/blob/main/client/API/quests.js): an export object where all the API calls (running through Axios for requests) available for a given endpoint are managed.

Back-end:
- [server.js](https://github.com/tspr0tege/quest-log/blob/main/server.js): the main Express server, which I've worked to keep as minimal as possible.
- [routes/quests.js](https://github.com/tspr0tege/quest-log/blob/main/server/routes/quests.js): different route endpoints for the "quests" API. Probably the most involved of all the scripts highlighted on this project.
- [models/quest.js](https://github.com/tspr0tege/quest-log/blob/main/server/models/quest.js): an example of a Sequelize model in use. Admittedly simplistic, but that's also what I'm aiming for.

The project has gone through a few iterations already, as I've been trying to work out how I want to structure things and what will be the most efficient for future expansion. As this is the first project of its kind that I've ever worked on it's been quite the bumpy journey, but I've learned a great deal from it at every step and don't regret a single thing.

## ​🇼​ork Experience

### Web Development Instructor
07/2021 - present
I hold tutoring session on the Wyzant platform, where I usually focus on my core JS skillset, but have been asked to assist in unfamiliar territory such as Python, or P5js. Which has so far proved successful.

Some of the things I've covered with clients can be seen on [my codepen profile: Code Create](https://codepen.io/code-create/pens/public).

### Andromeda 360
Aug 2022
I worked exclusively on the platform's front-end, addressing bugs, updating the UI, and implementing tests. Unfortunately a month after starting, the funding round did not succeed, and my position was eliminated. The experience remains invaluable, as the codebase and the people I worked with were amazing.

## ​🇪​ducation

Hack Reactor Javascript Immersive Course and Student Residency - Graduated April 2021

## 🔌 ​🇨​onnect

### [Email](mailto:squallpl1983@gmail.com)

### [Codepen.io](https://codepen.io/code-create/)

### [Connect on LinkedIn](https://www.linkedin.com/in/squall-leonhart/)
