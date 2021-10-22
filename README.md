# 05_MemoryGame

![](https://tenor.com/Ljaz.gif)
 
---
Índice

    1. Description
    2. User Definition & User Stories (UX)
    3. Aceptance Criteria
    4. Technical Requirements
    5. Hacker edition
    6. Expected Learning Outcomes
---

## 1. Description

Application to play Memory Game online! 

---

## 2. User Definition:
**User: will be defined for you ---**

Define in ReadMe a especific user.


## User Stories:

- The users wants to play a in-site game with a partner to spend time.

- The user wants to have a memory game that is about some topic regarding to it's interests.

- The user wants to see the game winner and loser by score, showing their names.

- Should be a reset button to play again and start a new game removing the scores but not the user names.

## 3. Acceptance Criteria

This applications should allow two users to play in-site web memory game, turning cards automatically if the card was not matching and leaving shown if it matches, each player should keep the score of how many have matched. The memory game should indicate when is turn of each one and by the end of the game should show the name of the winner and the score vs the loser. This product has to be delivered with an URL. The game must be full responsive, if playing in Ipad or in any desktop Size.

---

## 4. Technical Requeriments /

- Individual Programming
- Create a new repository from the starting using npm init.

- Install a testing framework.
- Install dependencies with ` npm install `
- Plan and execute Unit Testing
- Run Unit testing with ` npm test `

- Set a .gitignore file to avoid the node_modules to be uploaded in GitHub.
- Create the Release branch (to deliver and deploy) and the Development branch (to work on it daily).
- Make a full responsive website consider at least 2 types of dispositives, cellphone and desktop.
- Follow up Semantic HTML rules, have header, navigation bar, main, sections, asides, footer, etc.
- Create an Assets folder to store the img and sounds info for the game.
- Document every Agile SDLC steps on ReadMe.md. During the planning step document a screenshot of your Backlog & the prioritized agenda per each one.
- Create a memory.json data object to iterate and get dinamicallly the game cards info.
- Use Bootstrap Framework to speed your UI coding. Bootstrap is the unique library allowed.
- Two sprints of one week each one with Bilingual demo on Fridays by 9:00 am.
- For the second Demo, be ready to have testing users that will test your product and see your demo.

The _boilerplate_ should contains a file structure as a starting point like thisas all the sample dependencies and tests configuration:

```text
./
├── .editorconfig
├── .eslintrc
├── .gitignore
├── README.md
├── package.json
└── data
    ├── assets
    ├── memory.json
├── src
│   ├── app.js
│   ├── data.js
│   ├── index.html
│   ├── index.js
│   └── style.css
└── test
    ├── app.spec.js
    ├── headless.js
    └── index.html
```

### Scripts / Files

* `README.md`: should explain how to download, install and run the application
  as well as an introduction to the application, its functionality and decisions about
  design they took.
* `assets / memory.json`: Should be a JSON that contains the key: memory_game and the value is an Array of objects in which each object is a memory card that contains at least the properties of
* `src / index.html`: this is the entry point to your application. This file
  it must contain to _markup_ (HTML) and include the necessary CSS and JavaScript for index.js module.
* `src / app.js`: here you must implement the web application main functionality to manipulate the data coming from data.js
* `src / data.js`: here you must get the data from the local JSON and then export it to be used in the app.js module.
* `src / index.js`: here you must listen to DOM events, like create and add events to the DOM and get the search values to be processed to app.js
* `test / app.spec.js`: this file contains some sample tests and here you will have to implement the tests.

**CLUES:**
Follow the clues to create your own code, this clues can help you but you must create your own code, since this clues have different requirements.

- [Create a memory game with JS](https://dev.to/fakorededamilola/create-a-memory-game-with-js-1l9j)
- [How to build memory game](https://scotch.io/tutorials/how-to-build-a-memory-matching-game-in-javascript)
- [Some ideas](https://freefrontend.com/javascript-memory-games/)
- [Other memory game article ](https://medium.com/free-code-camp/vanilla-javascript-tutorial-build-a-memory-game-in-30-minutes-e542c4447eae)
- [ Free code camp Memory Game tutorial](https://www.freecodecamp.org/news/vanilla-javascript-tutorial-build-a-memory-game-in-30-minutes-e542c4447eae/)
- [ JSON ] (http://www.json.org/json-es.html)
- [ JSON FORMAT VALIDATOR](https://jsonformatter.curiousconcept.com/)


**Additional Resources**


These are some tips that can help you in organizing and carrying out your project, taking into account the development of your _soft skills_:

* To start an organization of your project, see with what resources
  accounts and the time you have to complete it.
* If there is something that you do not know, ask and try to solve it; you can start with
  a google search, then consulting your squad and finally your coach. 
  If there is something that I do not know, someone else can help me. Learning is a
  collaborative process.
* Once you start to move forward ask for feedback, your colleagues may have
  excellent ideas or ways to solve the project that can help you.
* When you run into a problem, look for alternatives, and for that, consult
  different sources.
* If you already see yourself investing a lot of time in details, you should know how to prioritize and
  stick with the most important, projects have limited time and you must
  know how to manage it.
* Work as a team, ask questions and try to complete the project without giving up.
* Prepare your presentation, if I cannot communicate my ideas to others I do not know
  You will appreciate all the effort and work you put into it.

---

## 5. Hacker Edition

---

You are not limited to implementing only the mandatory part. You can add also other nice to have functionalities on this web application, like a authentication login, a nice experience of gaming using sounds as effects and backgound music while playing.

---
##  6. Expected Learning Outcomes

---
- [ ] npm init 
- [ ] JSON 
- [ ] fetch() method
- [ ] promises in JavaScript 
- [ ] iterate data
- [ ] import & export modules
- [ ] My first Unitary Testing
- [ ] GitHub Branch Modeling > Development > Release 

---
# ReadMe

---

> This Readme should be replaced with the project documentation following the SDLC procedures for Agile Software Development Lyfe Cycle.


