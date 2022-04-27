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
- Movies List with signup and login + custom book list (using local storage to store users & books - no backend): https://typescript-movies-demo.vercel.app/ (multiuser app)
- Chat App (duplicate the browser tab to chat): https://rob-chat-sse.vercel.app/
- Tetris (React): https://tetris-clone.vercel.app/ (is also a great React State training!)
- Minesweeper (React): https://minesweeper-nine.vercel.app/ (is a good training for algorithms + React State)


### React with TypeScript

In a project React is very often used in combination with TypeScript instead of classical JavaScript.

Without getting into all the details, Typescript makes your code (much!) more robust by adding so called TYPES to your JavaScript code.

At the end of the day you can see your application as a big chain of calling functions, passing data around, changing data, returning data, displaying data. That is actually all there is.

So what do you guess is the most common ISSUE in our functions then?

In the IT world there is a famous meme called "SHIT IN -> SHIT OUT". Meaning: Incorrect INPUT data passed to a function will return incorrect OUTPUT. It is that simple.

TYPES will assure that you call your functions with CORRECT INPUT PARAMETERS throughout your code and also makes sure functions always RETURN the correct, expected OUTPUT DATA format.

By this simple "hardening" of your functions, probably 80% of issues in your application code can already be eliminated. Sometimes more, sometimes less. But definitely: It will impact the stability of your code massively.

Of course, sometimes also our functions PROCESS the data incorrectly, because we used wrong logic. This is something TypeScript cannot solve. At the end of the day, also SOME debugging fun must be left for us ;)


- TypeScript Intro - PlayList: https://www.youtube.com/watch?v=2pZmKW9-I_k&list=PLzAGFfNxKFuZgoZJPAfW_DeA2guNk849V

- React with TypeScript - Playlist: https://www.youtube.com/watch?v=TiSGujM22OI&list=PLC3y8-rFHvwi1AXijGTKM0BKtHzVC-LSK


### Git Development in a team

A guide with a real life, practical, hands-on process including all Git commands.

Setup and enjoy Team Development without worrying all the time about your next Git merge ;)

https://github.com/losrobbos/github-flow-guide/blob/main/GIT_WORKFLOW.github.md


### Code Formatting & Linting

In order to prepare for a TEAM project it is absolutely essential to have at least a basic understanding of the concepts of code formatting & linting.

Configure it just ONCE at the beginning of your project... and then forget about it and code happily ;)

Mini Guide to get going: https://github.com/losrobbos/code-formatting-and-linting


### Material UI

You have a project where you actually do not really care about an "original design"?

The use case is simply "clean & functional"?

Or you simply don't like spending to much time on styling at all?

Then give the "Material UI" package a shot.

With Material UI you can get - similar to Bootstrap - UI components out of the box, by simply "copy & paste & adapt". 

Material UI components also often bring some JavaScript logic out of the box, e.g. for picking a date from a calenader.

The Material UI package uses the famous "Material Design". 

The package was specifically developed for React.

Learning Material UI:

- Playlist: https://www.youtube.com/watch?v=BHEPVdfBAqE&list=PLC3y8-rFHvwh-K9mDlrrcDywl7CeVL2rO


## Advanced

### Fullstack Guides (Frontend, Backend, Deployment )

API Connect Guide: https://github.com/losrobbos/api-connect-guide

Vercel Deploy Guide: https://github.com/losrobbos/vercel-deploy-guide

Heroku Deploy Guide: https://github.com/losrobbos/heroku-node-deploy-guide

Databases - Getting started: https://github.com/losrobbos/databases-getting-started

Data Modeling samples: https://github.com/losrobbos/data-modeling-guide

API Prototyping: https://github.com/losrobbos/api-prototyping

Glossary (DCI): https://github.com/losrobbos/glossary


### File Uploads

In most web applications a user can signup and create a user profile.

If the user is able to generate contents, e.g. blog posts or cmments, usually the AVATAR image of that user will be shown. 
And the user should have the choice to upload an own image for that avatar.

Or the user wants to submit a recipe on a repices page, uploading an image of the final result of the recipe.

For use cases like this: We need to provide a FILE UPLOAD functionality.

File Uploads allow the user to pick an image from disk and upload it to a backend.

Find here a guide how you can realize a file upload fullstack, using React as the Framework, Express.js as the backend
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

So IF we change and re-organize that (the term for this is REFACTORING), we MUST make sure, that the OUTPUT of our code after that refactoring is the same as before! 

So all code which depends on that feature, will still work as before.

In order to give you safety for your refactoring, you need to ASSURE a certain output of your function(s).

You need .... a TEST! 

A TEST simply means, a piece of code which check if your feature code works like expected.

And you can use that piece of test code to check - after you have done all your changes & cleanings - if the feature code still works exactly as before.

So everybody can be safe to CHANGE their stuff and still make sure, they do not break anything with their change in the system.

That is it. That is the basic use case for testing: 
<b>ASSURING functionality, even after (a lot of) changes in the code structure</b>


Testing Concepts - a nice introduction:
- https://www.youtube.com/watch?v=r9HdJ8P6GQI


#### Testing JavaScript vanilla

Testing with JEST - Getting started guide:
- https://jestjs.io/docs/en/getting-started

#### Testing React

Playlist: 
https://www.youtube.com/watch?v=7dTTFW7yACQ&list=PL4cUxeGkcC9gm4_-5UsNmLqMosM-dzuvQ


### Game Development

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
- Enable 3D: https://enable3d.io/docs.html
  - Enable 3D Examples: https://enable3d.io/examples.html

Examples BabylonJS:
- https://www.babylonjs.com/games/

Examples Enable3D (with mouse movement you can change the view):
- 3D World: https://enable3d.io/examples/medieval-fantasy-book-standalone.html
- Water Waves Effect: https://enable3d.io/examples/water.html
- Physics with Ball: https://enable3d.io/examples/slope-angle-and-moving-platform.html
- Wall Crash: https://enable3d.io/examples/wrecking-ball-with-metal-chain.html
- Ego Shooter: https://enable3d.io/examples/first-person-shooter.html
- Mini Jump n'Run Game with Perspective Change (using F Keyboard Key): https://enable3d.io/examples/switch-camera-between-2d-and-3d.html


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
- keep the code EXTENDABLE, so we can add new features without the need to change all our code on new requirements 
- keep the app PERFORMANT, so it will not collapse if we get more and more active users 

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



### Architecture

For those who wanna step a little bit "outside the box" of just coding a feature or app and look at the broader picture on how to actually setup the FOUNDATION for a web project?

Design Patterns are an important part for that. But design patterns just address the code itself.

But often it is not just a well organized code in a tech stack, e.g. React for the Frontend & Java Spring for the Backend + a bunch of developers that will magically get you going.

We must come up with a general plan on HOW we wanna develop the software (= the process) and how we can develop it in a way to keep the complexity in check + the possibility to react to challenges, e.g. sudden unexpected traffic peaks for certain pages of our app, that starts loading super slow as a consequence.

And how do we deal with rising complexity as more and more features get added... and added... and added? 

How do we make sure, our app does not turn into a gigantic ball of mudd, causing chaos, panic and disorder in our team?

For this we need to think, apart from the code and its organisation, also about broader factors:

- Which parts of our app are performance critical and maybe need more resources than others?
- How do we decouple (=split) & integrate parts of our app, so they can be scaled indepenently?
- Which tech stack is best suited for our kind of user problems?
- Which external services we need and how do we integrate them?

All these are questions not primarily related to code. They are related to the overal plan, the overall ARCHITECTURE of our app.

Some nice resources:

- Domain Driven Design - Von Reallife Problemen zu Code Architektur (Book): https://www.amazon.de/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215/ref=sr_1_1?keywords=domain+driven+design&qid=1650536079&sprefix=domain+driven%2Caps%2C143&sr=8-1 
- Server im Web: Proxy vs Reverse Proxy (sehr anschaulich :)):
https://www.youtube.com/watch?v=MiqrArNSxSM
Event Driven Architecture: https://www.youtube.com/watch?v=STKCRSUsyP0 
- IT Architecture (Book): https://www.amazon.de/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420/ref=sr_1_1?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1C1UG06LG4U7O&keywords=martin+fowler&qid=1650534047&sprefix=martin+fowler%2Caps%2C93&sr=8-1
- Refactoring (Book): https://www.amazon.de/Refactoring-Improving-Existing-Addison-wesley-Signature/dp/0134757599/ref=sr_1_2?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1C1UG06LG4U7O&keywords=martin+fowler&qid=1650534047&sprefix=martin+fowler%2Caps%2C93&sr=8-2


### Further Topics

Some topics that are not handled yet here, but maybe are of more interest for you:
- Building desktop apps (like VsCode oder Slack) with Electron JS
- AI & Machine Learning
- Deployment Automation with CI / CD (Continuous Integration / Continuous Delivery)


I wish you a happy coding journey, may the code force be with you!
