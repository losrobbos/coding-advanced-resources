# Further Resources for the Programming Journey

Please find here some of my recommended resources for continuing your coding journey in JavaScript / TypeScript by self studying.

Following are some fields where you could go next (In case you do not have other plans already ;)):

- React & React TypeScript
- Team Development process
- Fullstack concepts (e.g. file upload)
- Smartphone development with React Native
- Fullstack development with NextJS
- Test Driven Development (TDD)
- Design Patterns
- Algorithms & Data Structures
- Application Architecture
- Game Development

Don't get overwhelmed by this huge amount of topics. 

Each topic alone could keep one busy for weeks (like React TypeScript) up to months or even years (like Algorithms or Game Development).

So with that list you could extend your own self-study curriculum to several years.

This guide will get updated from time to time with new resources.

## Most important JavaScript basics 

These are the most essential JS concepts in order to start with Framework Development (e.g. React or Express)

- Array Methods: map, filter, find, reduce
- Spread Operator ( the three Dots: ... )
- Destructuring (to extract data from objects & arrays into new variables)
- Functions (Arrow Functions, Parameters, Return, Callbacks)
- Event Listener ("click", "change")
- Event object (=> e.g. event.target to grab a clicked item)
- Promises (to "call" remote appliations, e.g. an API or a database)
- Fetch

## React

- Net Ninja: Modern React Development - Full Playlist: https://www.youtube.com/watch?v=j942wKiXFu8&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d
- Events (e.g. Click): https://www.youtube.com/watch?v=0XSDAup85SA&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d&index=7
- State & useState hook: https://www.youtube.com/watch?v=4pO-HcG2igk&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d&index=8
- useEffect hook: https://www.youtube.com/watch?v=gv9ugDJ1ynU&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d&index=14

### App ideas for training (from simple to more complex)

- Book List (one Page app): https://book-app-rose.vercel.app/
- Pizza List with Search & Pizza Cart (2 Pages app): https://pizza-store-two.vercel.app/
- Mini Blog with Details Page & Comments (2 Pages App): https://blog-fullstack-client.vercel.app/
- Location on a Map with OpenstreetMap & Leaflet: https://github.com/losrobbos/react-openstreetmap-demo
- Apartment Filtering by multiple criteria: https://booking-filter.vercel.app/
- Movies List with login & user specific contents (using local storage to store users & books - no backend): https://typescript-movies-demo.vercel.app/ (multiuser app)
- Chat App (duplicate the browser tab to chat): https://rob-chat-sse.vercel.app/
- Tetris (React): https://tetris-clone.vercel.app/ (is also a great React State training!)
- Minesweeper (React): https://minesweeper-nine.vercel.app/ (is a good training for algorithms + React State)

### Team Development

Most projects these days get developed in TEAMS.

Developing in teams is fundamentally different compared to working alone. A lot more things need to be considered before even starting (!) coding, otherwise you will probably produce a lot of conflicts :)

There are some fundamental decisions to take upfront:
- How to <b>align</b> all team members to a certain design?
- How to create & split <b>tasks</b> in the team?
- How to schedule meetings to track progress & discuss issues? Daily? Two times a day? Once a week? Or pair programming the whole day?
- How to use <b>Git</b> & GitHub in the team to bring our features together?
- How to setup simple rules for code <b>formatting</b> in order to prevent accidental file changes & merge conflicts?
- Assure usage of <b>same versions</b> of libraries for the whole team (e.g. no mix of React 17 and 18, Material UI 4 and 5, Node 12 and 16, etc)

And finally, for the role of the team lead: How to fill that role?

There are tons on books and articles on the subject of team leading, so this is pretty much out of scope here :)

But this video here nicely summarizes my own attitude how to interpret the leading role of a team: https://www.youtube.com/watch?v=jMpCF0Z623s

#### Design Mockup

In order to design an app with multiple pages, you usually create a MOCKUP.

A mockup is a first visual draft of ideally all your planned app pages / screens, maybe even adding the possibility to jump around in that draft by clicking links & buttons.

Especially in team development a mockup is very necessary to create a COMMON visual understanding of the app (and also the needed data and flow of data!)  and agree on basic design choices, like used colors & fonts.

A free, pretty famous & solid tool for that job is Figma. https://www.youtube.com/watch?v=eZJOSK4gXl4

But of course there are several other tools available to do this, like Adobe XD, Balsamiq or others. Pick your prefered one.

A mockup does not need to stay FIXED, of course, it can still be adapted throughout the project. But ideally you still spend quite some time on discussing the fundamental design principles UPFRONT of coding :)

Take your time on this and do not rush it through within one day. It will pay of significantly later on.

Some terminology:

- Wireframe: Just a very basics sketch of your screens, just sketching the LAYOUT
- Mockup: A wireframe + added colors, fonts and images to already create a real page feeling
- Prototype: An already ACTIONABLE version of the mockup where you can e.g. click on navigation links to get to other pages. Prototypes can either be just a basic, "clickable" design or already contain code for basic interaction.

#### Planning & Splitting tasks in a team

Planning of tasks nowadays is usally done using a <b>TICKET system</b>.

A ticket system simply collects TASKS - both urgent and more long term - from multiple sources (customer wishes / feedback, internal requirements).

In order to get a bit familiar on basic task management terminology, you might check out a short video first: https://www.youtube.com/watch?v=rIaz-l1Kf8w

A famous tool to get started with ticketing for a small project is Trello: https://trello.com/

Trello is really nice to quickly get started with basic ticket management terminology like Kanban.

In case you manage your code on GitHub you can also use GitHubs built in kind of "Trello": <b>Github Projects</b>.

Here you can link tasks in a repository to a KANBAN board and can automate the movement of the tickets.

Nice Step by Step Playlist on GitHub projects: 
https://www.youtube.com/watch?v=idZyqNIrt84&list=PLiO7XHcmTslc5hGrbnnmHIb0SeJLTpOEu

Once you do work in <b>Company teams</b>, you will find out, that <b>JIRA</b> is the most often used tool. 

JIRA is practially an industry standard and universally used in Team projects. 

It is slightly more complex than GitHub projects. But once you feel fine with GitHub Projects, you will also be quickly able to work with JIRA in a company.

You can also try out JIRA for free if you want: 

https://www.atlassian.com/de/software/jira

But most likely it will not be necessary to have JIRA experience to get your first project position.

#### Scheduling Meetings

In company projects the so called "Daily" is a common term. A short meeting in the morning, where we discuss our current status. 

In case of a finished feature we settle what we want to focus on next. And discuss any issues we have, both in code and in understanding (!) of tasks. Usually in a team we get fresh ideas on that that we coul not come up alone.

Especially the point of "understanding" a task is super important. Very often team members shy away from getting clarification on something they do not fully understand in an assigned task to prevent looking "dumb" or "weak".

But that false "pride" will sure-fire shoot you in the foot at some point of the project.

I love to torture people with clarification questions on given tasks, in order to get the best common understanding possible. Because I know from so many team projects, how much this is necessary. 

We do not need to discuss the nitty gritty implementation detail on code level. But on high level it should be clear how things in the app should behave, especially from a user perspective. If we understand the user perspective it will also help a lot when coding the feature.

Additional to the Daily Progress Meeting you could arrange another daily or bi-weekly "merge meeting" where we merge out feature branches together and also solve all the appearing conflicts together.

Dealing with code merge conflicts can be a very <b>intimidating</b> task and usually also needs some <b>clarification</b> between at least two members in the team on how to deal with the conflicting code parts. 

Therefore in the beginning of a project it is highly recommended to solve conflicting code parts together to prevent any nervous breakdowns :)

Lastly there is the possibility of "Pair Programming" where you code in pairs or even as a whole team together in a video session. 

That can make a lot of sense if people work toegther on the same page or feature (e.g. the frontend & backend part of the login page) 


#### Code Formatting & Linting

In order to prepare for a TEAM project it is absolutely essential to have at least a basic understanding of the concepts of code formatting & linting.

Configure it just ONCE at the beginning of your project... and then forget about it and code happily ;)

Mini Guide to get going: https://github.com/losrobbos/code-formatting-and-linting

#### Git Development in a team

A guide with a real life, practical, hands-on process including all Git commands.

Setup and enjoy Team Development without worrying all the time about your next Git merge ;)

https://github.com/losrobbos/github-flow-guide


### Material UI

You have a project where you actually do not really care about an "original design"?

The use case is simply "clean & functional"?

Or you simply don't like spending to much time on styling at all?

Then give the "Material UI" package a shot.

With Material UI you can get - similar to Bootstrap - UI components out of the box, by simply "copy & paste & adapt". 

Material UI components also often bring some JavaScript logic out of the box, e.g. for picking a date from a calendar.

The Material UI package uses the famous "Material Design". 

The package was specifically developed for React.

Learning Material UI:

- Playlist: https://www.youtube.com/watch?v=BHEPVdfBAqE&list=PLC3y8-rFHvwh-K9mDlrrcDywl7CeVL2rO


### React with TypeScript

In a project React is very often used in combination with TypeScript instead of classical JavaScript.

Without getting into all the details, Typescript makes your code (much!) more robust by adding so called TYPES to your JavaScript code.

At the end of the day you can see your application as a big chain of calling functions, passing data around, changing data, returning data, displaying data. That is actually all there is.

So what do you guess is the most common ISSUE in our functions then?

In the IT world there is a famous meme called "SHIT IN -> SHIT OUT". 

Meaning: Incorrect INPUT data passed to a function will return incorrect OUTPUT. It is that simple.

TYPES will assure that you call your functions with CORRECT INPUT PARAMETERS throughout your code and also makes sure functions always RETURN the correct, expected OUTPUT DATA format.

By this simple "hardening" of your functions, probably 80% of issues in your application code can already be eliminated. Sometimes more, sometimes less. But definitely: It will impact the stability of your code massively.

Of course, sometimes also our functions PROCESS the data incorrectly, because we used wrong logic. This is something TypeScript cannot solve. At the end of the day, also SOME debugging fun must be left for us ;)


- TypeScript Intro - PlayList: https://www.youtube.com/watch?v=2pZmKW9-I_k&list=PLzAGFfNxKFuZgoZJPAfW_DeA2guNk849V

- React with TypeScript - Playlist: https://www.youtube.com/watch?v=TiSGujM22OI&list=PLC3y8-rFHvwi1AXijGTKM0BKtHzVC-LSK



### Backend Topics

Before getting into backend development, it makes sense to WORK with backends from a frontend first in order to practice backend REQUESTS and how to process RESPONSES.

Understanding the request / response cycle for frontend / backend interaction and how to process the data in the frontend is critical and a good starting point for backend development.

Find here my API connect guide showing how you can:
- connect to an API using a tool (=REST Client)
- connect from JavaScript

API Connect Guide: https://github.com/losrobbos/api-connect-guide

For training these two resources are great:
- JSONPlacerholder API: Pick one of the listed APIs and make calls to it: https://jsonplaceholder.typicode.com/, e.g. https://jsonplaceholder.typicode.com/todos 
- JSON Server: Setup your OWN API on your PC with zero (!) code: https://github.com/typicode/json-server

Dealing with existing APIs will give you a good understanding of what the USE CASES of APIs are and how to deal with API resources before actually starting your dev journey. 

Enjoy!

#### Backend Development with JavaScript 

JavaScript / TypeScript can be used to code backends too.

In case you are not sure so far, if you wanna specialize on frontend or backend development in your career, 
it would make sense to learn backend coding with JAVASCRIPT first. That will be a lot easier compared to learning a brand new language. 

And you will learn all important backend concepts this way and will be able to also code backends in other languages at some point.

For the database MongoDB is naturally fitting for JavaScript, because in MongoDB you basically read & write JavaScript data. It will be very familiar.

Once you wanna FOCUS on backend development, so you wanna become a specialized backend developer, you will have to learn at least one further language. And additionally at least one SQL database (it doesn't matter much which one, but PostgreSQL or MySQL are natural first choices).

Most used languages for backend development:
- Java
- PHP
- C#
- Python
- Go

Common databases:
- PostgreSQL
- MySQL

But the language, like usual, is not enough. Together with the language you need to learn a backend framework.

Popular Frameworks:
- Java => Spring
- PHP => Laravel, Symfony
- C# => .NET
- Python => Django / Flask

Caching & Messaging:
- Redis


#### The two main API patterns

There are two main approaches how you can build a DATA SERVER (=API) for your frontend.

You can either build a <b>REST</b> or <b>GraphQL</b> API. 

Both of these API patterns do the same thing at the end. But their setup & architecture is pretty different.

The difference explained + demo of both: https://www.youtube.com/watch?v=PeAOEAmR0D0

GraphQL solves one fundamental problem of REST though. It ships with a tool which will document the API out of the box. So it makes it way easier for frontend developers to checkout how to retrieve data from the API in the format they need and EXPLORE with requests online easily, before they do the same in code.

Building a REST Api with JS Step by Step (the series is a bit dated in the used syntax, but the concepts are still valid & explained very well):
https://www.youtube.com/watch?v=0oXYLzuucwE&list=PL55RiY5tL51q4D-B63KBnygU6opNPFk_q

Building a GraphQL API Step by Step (PLayList): 
https://www.youtube.com/watch?v=Y0lDGjwRYKw&list=PL4cUxeGkcC9iK6Qhn-QLcXCXPQUov1U7f

Example GraphQL project developed in branches step by step: 
https://github.com/losrobbos/graphql-server-in-steps

## Deployment

Deployment simply means: Bring your app online :)

There are a lot of free providers for deploying your frontend & backend apps.

For frontends e.g. you can use Vercel, which works extremely well for REACT deployments.

For backend deployment Heroku is still one of the most solid options (even though you can also deploy simple backends using Vercel too!)

- Vercel Deploy Guide: https://github.com/losrobbos/vercel-deploy-guide
- Heroku Deploy Guide: https://github.com/losrobbos/heroku-node-deploy-guide



## Advanced

### Fullstack Guides (Frontend, Backend )

Databases - Getting started: https://github.com/losrobbos/databases-getting-started

Data Modeling samples: https://github.com/losrobbos/data-modeling-guide

API Prototyping: https://github.com/losrobbos/api-prototyping

Glossary (DCI): https://github.com/losrobbos/glossary


### File Uploads

In most web applications where user can create contents, we need to provide FILE UPLOAD functionality.

E.g. the user can pick a personal AVATAR image for its profile or upload a recipe image for a recipe page.

File Uploads allow the user to pick an image from disk and send it over to a backend. The backend then stores it, either on DISK or in a DATABASE.

Find here a guide how you can realize a file upload fullstack, using React for the Frontend, Express.js as the backend
and a file cloud provider to store the files in the cloud for free:

https://github.com/losrobbos/file-upload-guide


### NextJS

NextJS is a React FRAMEWORK, so it is built upon React, adding some very handy extra features.

Features you get out of the box:
- Routing (no React-Router-DOM)
- Server Side Rendering (for Search Engine optimization)
- API routes (integrated backend functions!)
- Authentication between Frontend & Backend

For me personally NextJS makes me probably 50% more productive, compared to normal React development. I absolutely love it!

It takes away a lot of default work for me, which I usually need to setup & configure painfully on a new project, like routing or providing several authentication methods. 

That alone makes it much more fun for me to develop in NextJS, because I can pretty much focus on my app logic right away, without all that draining "standard tasks" setup.

Learning NextJS:

- Playlist: https://www.youtube.com/watch?v=9P8mASSREYM&list=PLC3y8-rFHvwgC9mj0qv972IO5DmD-H0ZH


### React Native

With React Native you can build up on all your - earned by sweat, pain and nervous breakdowns - gained React knowledge... and now build smartphone apps!

I got a React Native "Getting started" guide here, which might be helpful as preparation, before you get into the official docs:

https://github.com/losrobbos/react-native-guide


### Test Driven Development

Let's say you invested dozens of hours into this nice feature.

Your code works "fine" at the end. The feature works in the browser.

You pushed it. And it gets released. The world is fine.

But then you realize: DAMN! This code is a bit messy. It works. But probably it needs quite some restructuring and polishing.

But if we are working in a TEAM PROJECT we could get into a serious problem now.

Our nice feature is important. In the meantime others have already built up new features based on your feature! So work of others DEPENDS on that feature to be working like expected.

So IF we change and re-organize that (the term for this is REFACTORING), we must make sure, that the OUTPUT of our code after that refactoring is the same as before!

So all code which DEPENDS on that feature (either code from you or your team mates), will still work as before too!

In order to give you safety for your refactoring, you need to ASSURE a certain output of your function(s).

You need .... a TEST! 

A TEST simply means: A piece of Code. A piece of code which checks if your feature code works like expected.

You can use that piece of test code to check - after you have done all your changes & cleanings - if the feature code still works exactly as before.

And the nice thing is: This TESTING can be automated. Meaning: Once you have written a test you can check AGAIN and AGAIN that your code works like expected, automatically.

And if you write tests for literally ALL your functions in your app, you basically have assured the OVERAL functionality of your app.

So with that process in place, everybody in the team can be safe to not just add but also CHANGE stuff in the app. 

The TESTS will make (almost) sure, nothing gets broken in the system.

That is it. 

That is the basic use case for testing: 

<b>ASSURING functionality, even after (a lot of) changes in the code structure</b>


Testing Concepts - a nice introduction:
- https://www.youtube.com/watch?v=r9HdJ8P6GQI


#### Testing JavaScript vanilla

Testing with JEST - Getting started guide:
- https://jestjs.io/docs/en/getting-started

#### Testing React

Playlist: 
https://www.youtube.com/watch?v=7dTTFW7yACQ&list=PL4cUxeGkcC9gm4_-5UsNmLqMosM-dzuvQ

#### Testing Antipatterns

Testing can also be overengineered: https://www.youtube.com/watch?v=UWtEVKVPBQ0.


### Game Development

Game development is a fantastic challenge to get your programming to the next level.

In Game Development also the topics of ALGORITHMs and DESIGN Patterns can be nicely trained (see the following chapters in the guide)

For little Games without "enemies" you can try to use VanillaJS / DOM in the Browser or React.

Examples:

- Snake: https://eddornelas.github.io/Snake-Game-Demo/
- Tetris (React): https://tetris-clone.vercel.app/ (is also a great React State training!)
- Minesweeper (React): https://minesweeper-nine.vercel.app/ (is a good training for algorithms + React State)

For a little more interactivity (e.g. collisions with moving items or enemies) it will be a lot easier to use a game library (often called "game engine")


#### 2D Game Engines

- Phaser: https://phaser.io/examples
- Kaboom: https://kaboomjs.com/

Examples:

- Mario Game (Kaboom): https://leongeldsch.github.io/mario/

#### 3D Game Engines

- BabylonJS: https://doc.babylonjs.com/start
  - Babylon has a great Step by Step guide with a playground, where you can test things out easily: https://doc.babylonjs.com/
- Enable 3D: https://enable3d.io/docs.html
  - Enable 3D Examples: https://enable3d.io/examples.html

Babylon Examples: 
  - https://www.babylonjs.com/games/

Examples Enable3D (with mouse movement you can change the view):
- 3D World: https://enable3d.io/examples/medieval-fantasy-book-standalone.html
- Water Waves Effect: https://enable3d.io/examples/water.html
- Physics with Ball: https://enable3d.io/examples/slope-angle-and-moving-platform.html
- Wall Crash: https://enable3d.io/examples/wrecking-ball-with-metal-chain.html
- Ego Shooter: https://enable3d.io/examples/first-person-shooter.html
- Mini Jump n'Run Game with Perspective Change (using F Keyboard Key): https://enable3d.io/examples/switch-camera-between-2d-and-3d.html

My currently preferred engine is <b>BabylonJS</b>, due to the superb documentation & easy to follow guides.


### Algorithms & Data Structures 

In the "real world" you sometimes face problems that could not be solved by looping over an array or counting up some numbers.

Sometimes we get a bit more complicated structures, e.g. like this object:

```
  {
     "name": "Grandparent", children: [
        { name: "Sally" },
        { name: "Harry", children: [
            { name: "Melinda" }, { name: "Harry Jr" } 
        ]}, 
     ]
  }

```

Here we have a Granparent object with children, where again each child can have children. And so on.

Challenge: How can you now get a FLAT array with the names of ALL members out of this family "structure"?

Okay. You could use simply nested FOR loops to loop through each "level". And add each found item to a new array. That is it. Right?

But then you have to know IN ADVANCE, how deep the family tree goes! 

In case we got three levels down, we need 3 for loops. But on another family we might need to go 8 levels down... and then we need 8 (!) nested for loops!

So how can we write just ONE piece of code, that will collect all the members on all levels independent on how many levels we have here....!

If we just know loops and functions it will not help much.

So we reached a classical "algorithmical challenge". 

And therefore we need to understand a bit more on <b>DATA STRUCTURES</b>. E.g. the one above is a so called TREE. 

And then we need to know a bit on how to work with these data structures, e.g. to search inside them or convert them into something else. 

For that part we need to know about <b>ALGORITHMS</b>.

- Big Overview / Introduction DataStructures: https://www.youtube.com/watch?v=41GSinwoMYA
- Common Data Structures (non JS): https://www.youtube.com/watch?v=41GSinwoMYA&t=2479s (same video as before, round about 40 min)
- Common Data Structures (great playlist): https://www.youtube.com/watch?v=Sk3MxEUSwY4&list=PLpWvGP6yhJUhC1SpdouTObbd5yGgV4opL&index=1
- Algorithms Step by Step (great playList): https://www.youtube.com/watch?v=LuXCJxY7nPE&list=PLn2ipk-jqgZiAHiA70hOxAj8RMUeqYNK3&index=3

#### Coding Challenges online

- Exercism: https://exercism.org/tracks/javascript/exercises
- Codewars: https://www.codewars.com/join
- Edabit: https://edabit.com/challenges/javascript
- Hackerrank: https://www.hackerrank.com/

#### Courses + Books

- Academind: Datastructures  https://pro.academind.com/p/javascript-datastructures-the-fundamentals
- Academind: Algorithms (JavaScript): https://pro.academind.com/p/javascript-algorithms-the-fundamentals
- Book - Algorithms & Data Structures: https://www.amazon.de/Common-Sense-Guide-Structures-Algorithms-Second/dp/1680507222/ref=sr_1_6?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=algorithmen+und+datenstrukturen&qid=1650527384&sr=8-6
- Book - Algorithmen for Dummies (deutsch) - mit Reallife Bezug und Humor ;): https://www.amazon.de/Algorithmen-Datenstrukturen-Dummies-Andreas-Gogol-D%C3%B6ring/dp/3527714324/ref=sr_1_1?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=2QZM3C9T92QKN&keywords=algorithmen+und+datenstrukturen&qid=1650525285&sprefix=algorithmen+und+datenstrukturen%2Caps%2C87&sr=8-1 



### Design Patterns

Design patterns are patterns for designing the code for your application. Straight and simple.

We all know the design of a webpage in the browser. But what does "design the code" mean? 

It sounds a bit weird. Does it mean to style your code with CSS? Nope :)  

So let's start with the problem.

We all know - You often need to COMBINE functions and classes in a way to create an application that solves problems of a user.

Writing code that realizes some feature is just ONE part of the game. But often it is not straight forward, how to ARRANGE classes and functions to work together.

And even if we get our feature "somehow" working: That does not mean we are done with it forever.

Unfortunately we cannot just code our app features once and forget about it.

Once the app is deployed and users actually start USING it, we will need to CONTINUE working on the code.

Meaning: Fixing bugs of existing features. Refactoring not optimal code, e.g. for performance optimization. Adding new features on top of existing features.

So we get these common problems we need to tackle:

- solve the user problems by CREATING & ARRANGING our classes and functions to work together properly 
- keep the code FLEXIBLE & EXTENDABLE, so we can add new features without the need to change all our code structure on new requirements 

And we are lucky.

Most problems of these kind have already been solved in the past.

And the lessons and "patterns" that came out of that are: Design Patterns. 

Design patterns are suggestions on how to write software to fulfill the goals above.

We have two base programming techniques of producing code:
- Object Oriented Programming (OOP)
- Functional Programming (FP)

For both of these "paradigms" we would apply different patterns, as OOP and FP code structures differ quite a bit.

Therefore the FIRST design choice is: Functional Programming vs OOP vs a mix of both (=hybrid)

For languages like JavaScript we could use patterns from BOTH worlds, because JS allows a mixture of functional & OOP programming.

So it makes sense to learn some OOP design patterns, even if you are mostly just coding functions. At some point classes might get handy too, to solve specific problems.

#### OOP Design Patterns

There is a very famous standard book for OOP design patterns by the "Gang of Four" (often called just GoF).

Another famous series of patterns are the <b>SOLID</b> principles.

Now getting into all that design patterns (several dozen) without any concrete real life use case at hand would probably be a bit overkill at first.

In order to get into design patterns, you can also start with a YouTube playlist which will make the topic a bit more accessible ;)

Playlist - Design Patterns - some famous "Gang of Four" design patterns + the SOLID design patterns:

https://www.youtube.com/watch?v=BWprw8UHIzA&list=PLZlA0Gpn_vH_CthENcPCM0Dww6a5XYC7f

#### Pure Functional Programming (no OOP)

In case you wanna do "all functional" or just mostly functional, it might make sense to dive a little bit into some functional programming paradims:

- Functional Programmers Toolbox: https://www.youtube.com/watch?v=Nrp_LZ-XGsY
- Function Composition: https://www.youtube.com/watch?v=rCKPgu4DvcE



### Architecture

At some point you might be ready.

You coded all that little apps.

You mastered a lot of different code tasks in your life.

Are you ready to go all-in now?

For those wanna step a little bit "outside the box" of just coding a feature in a team or creating own small web apps... it is time to look at the broader picture on how to actually setup the INFRASTRUCTURE for more complex web projects. 

Once you reach that step, you might be ready for an architect position or lead development.

Design Patterns are an important part of that. But design patterns just address the code itself.

It is not enough to just rely on well written code in some tech stack, e.g. React for the Frontend & Java Spring for the Backend + a bunch of developers that will magically get you going.

Fist we must come up with a general plan on HOW we wanna develop the software, with a process that fits to the development goals. 

And how we can develop it in a way to keep the performance & complexity in check + the possibility to react to challenges? (e.g. sudden traffic peaks for certain pages of our app, that start loading super slow)

And how do we deal with rising complexity as more and more features get added... and added... and added? 

Will our app still SCALE well, meaning: Will it not significantly SLOW DOWN or become more and more ERROR prone with more and more features, connected services, registered users and involved developers?

How do we make sure, our app does not turn into a gigantic ball of mudd, causing chaos, panic and disorder in our team?

For this we need to think, apart from the code and its organisation, also about broader factors:

- Which parts of our app are performance critical and maybe need more resources than others?
- How do we decouple (=split) & integrate parts of our app, so they can be scaled indepenently?
- Which tech stack is best suited for our kind of user problems?
- Which external services we need and how do we integrate them? Do we use Providers like AWS, Azure or Google Cloud for hosting & scaling our app?

All these are questions not primarily related to code. They are related to the overal plan, the overall ARCHITECTURE of our app.



Some nice resources:

- Domain Driven Design - Von Reallife Problemen zu Code Architektur (Book): https://www.amazon.de/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215/ref=sr_1_1?keywords=domain+driven+design&qid=1650536079&sprefix=domain+driven%2Caps%2C143&sr=8-1 
- The very basics of Servers in the web: Proxy vs Reverse Proxy:
https://www.youtube.com/watch?v=MiqrArNSxSM
- Microservices architecture for complex backends - Intro (Martin Fowler): https://www.youtube.com/watch?v=2yko4TbC8cI 
- Serverless vs Microservices - High Level: https://www.youtube.com/watch?v=EpW28dvm_qo
- Event Driven Architecture (Martin Fowler): https://www.youtube.com/watch?v=STKCRSUsyP0 
- Automating Software Deployments using "Continuous Delivery" (Martin Fowler): https://www.youtube.com/watch?v=aoMfbgF2D_4
- Microservices architecture step by step (great playlist): https://www.youtube.com/watch?v=D-Hw_CopGDs&list=PLzERW_Obpmv81N-F8yBowb_QHvf9ISG7y

Books: 
- Enterprise Architecture Patterns: https://www.amazon.de/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420/ref=sr_1_1?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1C1UG06LG4U7O&keywords=martin+fowler&qid=1650534047&sprefix=martin+fowler%2Caps%2C93&sr=8-1
- Refactoring: https://www.amazon.de/Refactoring-Improving-Existing-Addison-wesley-Signature/dp/0134757599/ref=sr_1_2?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1C1UG06LG4U7O&keywords=martin+fowler&qid=1650534047&sprefix=martin+fowler%2Caps%2C93&sr=8-2


### Further Topics

Some topics that are not handled yet here, but maybe are of more interest for you:
- Building desktop apps (like VsCode oder Slack) with Electron JS
- AI & Machine Learning
- Deployment Automation with CI / CD (Continuous Integration / Continuous Delivery)


I wish you a happy coding journey, may the code force be with you!
