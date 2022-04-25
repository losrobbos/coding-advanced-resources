# Further Resources for the Programming Journey

Please find here some of my recommended resources for continuing your coding journey in JavaScript / TypeScript by self studying.

## Most important JavaScript basics 

These are the most essential JS concepts in order to start with Framework Development (e.g. React or Express)

- Array Methods: map, filter, find, reduce
- Spread Operator ( the three Dots: ... )
- Functions (Arrow Functions, Parameters, Return, Callbacks)
- Event Listener ("click", "change")
- Event object (=> e.g. event.target to grab a clicked item)
- Promises
- Fetch

## React

- Net Ninja: Modern React Development - Full Playlist: https://www.youtube.com/watch?v=j942wKiXFu8&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d
- Events (e.g. Click): https://www.youtube.com/watch?v=0XSDAup85SA&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d&index=7
- State & useState hook: https://www.youtube.com/watch?v=4pO-HcG2igk&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d&index=8
- useEffect hook: https://www.youtube.com/watch?v=gv9ugDJ1ynU&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d&index=14

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

### NextJS

NextJS is a React FRAMEWORK, so it is built upon React, adding some very handy extra features.

Features you get mostly out of the box:
- Routing (no React-Router-DOM)
- Server Side Rendering (for Search Engine optimization)
- API routes (integrated backend functions!)

Learning NextJS:

- Playlist: https://www.youtube.com/watch?v=9P8mASSREYM&list=PLC3y8-rFHvwgC9mj0qv972IO5DmD-H0ZH


### React Native

With React Native you can build on all your nice, built-up React knowledge... and build smartphone apps.

I got a React Native "Getting started" guide here, which might be helpful as preparation, before you get into the official docs:

https://github.com/losrobbos/react-native-guide


### Test Driven Development

Let's say you invested dozens of hours into this nice feature.

Your code works "fine" at the end. The feature works in the browser.

But then you realize: DAMN! This code is a bit messy. It works. But probably it needs quite some restructuring and polishing.

All good.

But if we are working in a TEAM PROJECT we could get into a serious problem now.

Our nice feature is important. Work of others DEPENDS on that!

So IF we change and re-organize that (the term for this is REFACTORING), we MUST make sure, that the OUTPUT of that refactoring is the same as before! So all code which depends on my code, will still work as before.

In order to give you safety for your refactoring, you need some sort of hallmark to check against

You need .... a TEST! 

YES!

A TEST simply means, a piece of code to check if your code works like expected.

And you can USE that piece of code to check - after you have done all your changes & cleanings - if the code STILL works exactly as before.

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

And therefore we need to understand a bit more on datastructures. E.g. the one above is a so called TREE. 

And then we need to know a bit on how to work with these data structures, e.g. to search inside them or convert them into something else. 

For that part we need to know about <b>ALGORITHMS</b>.

- Big Overview / Introduction DataStructures: https://www.youtube.com/watch?v=41GSinwoMYA
- Common Data Structures (non JS): https://www.youtube.com/watch?v=41GSinwoMYA&t=2479s (same video as before, round about 40 min)
- Common Data Structures (great playlist): https://www.youtube.com/watch?v=Sk3MxEUSwY4&list=PLpWvGP6yhJUhC1SpdouTObbd5yGgV4opL&index=1
- Algorithms Step by Step (great playList): https://www.youtube.com/watch?v=LuXCJxY7nPE&list=PLn2ipk-jqgZiAHiA70hOxAj8RMUeqYNK3&index=3

### Coding Challenges online

- Edabit: https://edabit.com/challenges/javascript
- Hackerrank: https://www.hackerrank.com/

### Algos & DS Courses & Books

- Academind: Datastructures  https://pro.academind.com/p/javascript-datastructures-the-fundamentals
- Academind: Algorithms (JavaScript): https://pro.academind.com/p/javascript-algorithms-the-fundamentals
- Book - Algorithms & Data Structures: https://www.amazon.de/Common-Sense-Guide-Structures-Algorithms-Second/dp/1680507222/ref=sr_1_6?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=algorithmen+und+datenstrukturen&qid=1650527384&sr=8-6
- Book - Algorithmen for Dummies (deutsch) - mit Reallife Bezug und Humor ;): https://www.amazon.de/Algorithmen-Datenstrukturen-Dummies-Andreas-Gogol-D%C3%B6ring/dp/3527714324/ref=sr_1_1?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=2QZM3C9T92QKN&keywords=algorithmen+und+datenstrukturen&qid=1650525285&sprefix=algorithmen+und+datenstrukturen%2Caps%2C87&sr=8-1 


### Pure Functional Programming (no OOP)

- Functional Programmers Toolbox: https://www.youtube.com/watch?v=Nrp_LZ-XGsY
- Function Composition: https://www.youtube.com/watch?v=rCKPgu4DvcE


### Architecture

- Domain Driven Design - Von Reallife Problemen zu Code Architektur (Book): https://www.amazon.de/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215/ref=sr_1_1?keywords=domain+driven+design&qid=1650536079&sprefix=domain+driven%2Caps%2C143&sr=8-1 
- Server im Web: Proxy vs Reverse Proxy (sehr anschaulich :)):
https://www.youtube.com/watch?v=MiqrArNSxSM
Event Driven Architecture: https://www.youtube.com/watch?v=STKCRSUsyP0 
- IT Architecture (Book): https://www.amazon.de/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420/ref=sr_1_1?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1C1UG06LG4U7O&keywords=martin+fowler&qid=1650534047&sprefix=martin+fowler%2Caps%2C93&sr=8-1
- Refactoring (Book): https://www.amazon.de/Refactoring-Improving-Existing-Addison-wesley-Signature/dp/0134757599/ref=sr_1_2?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1C1UG06LG4U7O&keywords=martin+fowler&qid=1650534047&sprefix=martin+fowler%2Caps%2C93&sr=8-2


### Game Development

For little Games like Snake you can try to use VanillaJS / DOM in the Browser

For a little more interactivity (e.g. Kollisionen with moving items or enemies) it makes it a lot easier to use a Game library (often called "engine")

#### 2D Engines

- Phaser: https://phaser.io/examples
- Kaboom: https://kaboomjs.com/

#### 3D Engines

- Enable 3D: https://enable3d.io/docs.html
  - Enable 3D Examples: https://enable3d.io/examples.html


