# Developer diary 🟩

### Jul. 24
- started [TOP Express 105: Forms And Deployment](https://www.theodinproject.com/lessons/nodejs-express-105-forms-and-deployment) lesson, which touches on server-side form sanitization and validation
    - kept working through the [MDN guided library project](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/forms). The [challenge yourself](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/forms#challenge_yourself) and deployment sections are remaining.
    - validation vs sanitization refresher by MDN:
        > Before the data from a form is stored it must be validated and sanitized:
        > - Validation checks that entered values are appropriate for each field (are in the right range, format, etc.) and that values have been supplied for all required fields.
        > - Sanitization removes/replaces characters in the data that might potentially be used to send malicious content to the server.
- discovered the following html elements:
    - dl: description list
    - dt: description term
    - dd: description details
    
### Jul. 23
- completed [TOP Express 104: View Templates](https://www.theodinproject.com/lessons/nodejs-express-104-view-templates) lesson
- learned about [how to manage asynchronous operations in controller functions](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Displaying_data/flow_control_using_async)
    - installed the async module
    - discovered the following methods: async.parallel(), async.series(), async.waterfall()
- reviewed Pug basics: syntax, variables, loops, conditionals...
- tried out the Luxon library

### Jul. 19
- slowed down over the past week because of the heat wave *(and recruiting processes!)*, but I'm now back in the coding pit!
- completed TOP Mini Message Board project: [instructions](https://www.theodinproject.com/lessons/nodejs-mini-message-board), [repo](https://github.com/tramio/TOP-mini-message-board), [deployment](https://fathomless-wildwood-44689.herokuapp.com/). It doesn't *look* mighty (it wasn't blessed by the CSS Gods), but does check the project requirements and that's all that matters - practiced Express routing, Pug templating and Heroku deployment!
- this project was my first try at using a templating engine
- escaping characters is useful to prevent XSS attacks
- Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into otherwise benign and trusted websites
- completed [Express 103: Routes and Controllers ](https://www.theodinproject.com/lessons/nodejs-express-103-routes-and-controllers)

### Jul. 16
- listened to the first episode of the season 9 of Command Line Heroes: [*Relentless Replicators*](https://www.redhat.com/en/command-line-heroes/season-9/relentless-replicators). This season is all about cybersecurity threats!
### Jul. 14
- read the Next.js documentation about font optimization and custom Document
- FCP stands for First Contentful Paint. Sites should strive to have a FCP of 1.8 seconds or less. https://web.dev/fcp/
- LCP stands for Largest Contentful Paint. Sites should strive to have a LCP of 2.5 seconds or less. https://web.dev/lcp/

### Jul. 10
- finished the lesson [Express 102: CRUD and MVC](https://www.theodinproject.com/lessons/nodejs-express-102-crud-and-mvc) from TOP. Coming back to Mongoose after having taken a step aside to learn TypeScript was painful at first _(types, interfaces, schemas, schema types... it's all about **types**)_, but at the end of the day, the knowledge of each of them helped cementing that of the other!
- also completed the lesson [Preparing for Deployment](https://www.theodinproject.com/lessons/nodejs-preparing-for-deployment) from TOP, which consisted of the following steps:
    - created a Heroku account
    - installed the Heroku CLI
    - added my SSH key to Heroku
- started the [Mini Message Board](https://www.theodinproject.com/lessons/nodejs-mini-message-board) project from TOP which involves the usage of a templating language; this isn't taught in TOP, and the choice of the templating language is left to the student. I chose Pug!
- started reading the Pug documentation

### Jul. 6
- spent the day building yet another version of my portfolio, this time with next.js and typescript! hoping to deploy it on vercel by the end of the week
- coming back to next.js after these past weeks learning node.js, mongoDB and express was a mindblowing experience — so many things clicked all of a sudden! not having to stick closely to the documentation to operate the tiniest changes was so freeing
- currently having some issues loading static assets, will fix this asap
- typescript is a whole new technology for me though
- watched TM's [TypeScript Crash Course](https://www.youtube.com/watch?v=BCg4U1FzODs)
  - typescript has type inference
  - got to understand the difference between TS interfaces and types
  - got to look up type assertions use cases
  - learned how to declare optional and readonly properties
  - interesting fact: typescript is included in angular projects by default
- RFC stands for Request For Comments
- having an interview tomorrow! also prepared for it.

### Jul. 5
- read the article [Using middleware](https://expressjs.com/en/guide/using-middleware.html) from the Express documentation, which concludes the lesson [Express 101](https://www.theodinproject.com/lessons/nodejs-express-101) from TOP

### Jul. 4
- completed the optional assignments from [TOP Introduction to Express](https://www.theodinproject.com/lessons/nodejs-introduction-to-express)
  - finished watching Traversy Media's [Express crash course](https://www.youtube.com/watch?v=L72fhGm1tfE)
  - watched Web Dev Simplified's [Learn Express JS In 35 Minutes](https://www.youtube.com/watch?v=SccSCuHhOw0) video
    - static routes should be declared above dynamic routes
  - also watched Web Dev Simplified's video [Why You Don't Want To Work In FAANG](https://www.youtube.com/watch?v=twKrik7KY6Y), which I found quite interesting and recommend to anyone, whether in the tech industry or not!
- started the lesson [Express 102: CRUD and MVC](https://www.theodinproject.com/lessons/nodejs-express-102-crud-and-mvc) from TOP
  - MVC stands for Model, View, Controller and refers to the architecture of your code. It is a way to organize your application by separating all of the actions into 3 main components: Models, Views and Controllers.
  - watched WDS' [Mongoose Crash Course](https://www.youtube.com/watch?v=DZBGEVgL2eE) twice

### Jul. 2
- started the lesson [Express 101](https://www.theodinproject.com/lessons/nodejs-express-101) from TOP
  - read MDN's [introduction to their Express Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Tutorial_local_library_website)
  - started coding along [the second part of the introduction](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/skeleton_website)

### Jul. 1
- completed chapter 6, and thereby finished the [MongoDB Basics (M001)](https://university.mongodb.com/courses/M001/about) course! grade was 97%, downloaded the proof of completion.
- completed the compulsory assignments from [TOP Introduction to Express](https://www.theodinproject.com/lessons/nodejs-introduction-to-express)
  - read [MDN Express/Node introduction](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)
  - read and coded along [MDN Setting up a Node development environment](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/development_environment#using_npm). notably installed the Express Application Generator: this tool generates an Express application "skeleton"
  - refactored by [Basic Informational Website project](https://github.com/tramio/TOP-basic-informational-site) into an Express app
- looking forward to starting the optional assignments tomorrow! these are Express crash courses from the excellent teachers Traversy Media and Web Dev Simplified

### Jun. 30
- coworked with my road-to-webdev companion
- completed chapters 4 and 5 from [MongoDB Basics (M001)](https://university.mongodb.com/courses/M001/about)
- $ signifies that you are looking at the value of a field rather than its name
- $ denotes an operator
- $push adds an element to an array
- $push turns a field into an array field if it was previously a different type
- array operators: $all, $size 
- use $size to specify the length of the queried array
- use a projection to display only the fields you want in the cursor
- db.<collection>.find({query}, {projection}) to specify which fields should or should not be included in the result cursor
- projections cannot mix inclusion and exclusion, except for "{_id : 0", <field> : 1}"
- $elemMatch can be used both in query and projection. it matches documents that contain an array field with at least one element that matches the specified query criteria
- $expr, $regex, $match, $group
- aggregation framework
- .sort() : 1 for increasing order, -1 for decreasing order
- .method()
- when using .sort() and .limit(), mongoDB assumes that .sort() precedes .limit()
- learned how to create indexes
- learned how to use upsert

### Jun 29, 2022
- completed the chapters 2 and 3 and started the chapter 4 from [MongoDB Basics (M001)](https://university.mongodb.com/courses/M001/about)
  - GUI (Graphical User Interface): a graphics-based operating system interface that uses icons, menus and a mouse to manage interaction with the system
  - use **mongorestore** to import and **mongodump** to export bson
  - use **mongoimport** to import and **mongoexport** to export json
  - a namespace concatenates a database name and collection name
  - the default value for the _id identifier is of type ObjectId()
  - use .findOne() to get a random document from a collection
  - .insert()
  - if a document is inserted without a provided _id value, then the _id field and value will be automatically generated for the document before insertion
  - insertion: ordered by default. if duplicate ids, the process is hold
  - use {"ordered": false} to disable ordered insertion
  - attempting to insert a document in a collection that doesn't exist creates a collection
  - similarly, use [databasethatdoesn't exist] will create that database
  - hopefully, that newly created db won't appear in my dbs as long as no data is associated with it (no document was inserted)
  - multiple documents can be inserted by means of an array
  - collections and databases are created when they are being used: `use tools` followed by db.tractors.insert({<tractor doc}) creates the tools.tractors namespace
  - update operators: $set, $inc, $push
  - MQL: MongoDB Query Language
  - use db.<collection>.drop() to delete a collection
  - use .deleteOne() or .deleteMany() to delete document(s)
  - comparison operators: $eq, $ne, $gt, $lt, $gte, $lte
  - logic operators: $and, $or, $nor, $not
  - $and is implicit by default
- gotta look further into $not

### Jun 28, 2022
- started TOP [Introduction to MongoDB](https://www.theodinproject.com/lessons/nodejs-introduction-to-mongodb) which consists in...
- taking the [MongoDB Basics (M001)](https://university.mongodb.com/courses/M001/about) course from the MongoDB University! I completed the chapter 1 today, 7 more to go!
  - MongoDB is a NoSQL documentDB where documents are stored in collections
  - created a workspace and a cluster
- quickly researched what CS50 is, and why it is so popular among webdev learners. In short: it is Harvard's introductory course to computer science, the exact same that CS students take in uni. It is available for free online, self-paced, and has an approximate duration of 11 weeks for a time commitment of 10 to 20 hours per week. Despite being intended for beginners it is believed to be quite hard still, but very useful to have a healthy taste of data structures, algorithms, and how languages work under the hood. I may have a look into it someday!

### Jun 27, 2022
- completed TOP [Basic Informational Site](https://www.theodinproject.com/lessons/nodejs-basic-informational-site) project ([repo](https://github.com/tramio/TOP-basic-informational-site), [demo](https://top-basic-informational-site.tramio.repl.co/))! Although this Node website looks very simple, I've struggled a lot with error handling debugging. The gap between theory and practice was real!
- my [PR](https://github.com/microsoft/vscode-docs/pull/5423) on the VS Code documentation repo was merged
- created a MongoDB account
- WHATWG stands for *Web Hypertext Application Technology Working Group*. It is a community of people interested in evolving HTML and related technologies. It was founded by individuals from Apple, Mozilla and Opera in 2004.
- The node:url module provides two APIs: a legacy API that is Node.js specific, and a newer API that implements the same WHATWG URL Standard used by web browsers.
- in Node, with response.writeHead(), I can set my statusCode, statusMessage as well as an object or array of headers
- this has greater precedence than response.setHeader()
- a tuple is a data structure consisting of multiple parts
- REPL stands for *read-evaluate-print loop*

### Jun 24, 2022
- CRUD stands for create, read, update, delete.
- read [Node.js debugging in VS Code](https://code.visualstudio.com/docs/nodejs/nodejs-debugging)
- read [Debugging a Node.Js app using Chrome Dev Tools](https://www.section.io/engineering-education/debug-node-devtools/) by Geoffrey Mungai
- finished TOP lesson [Debugging Node](https://www.theodinproject.com/lessons/nodejs-debugging-node). I can now debug Node with the VS Code built-in debugger or the Chrome DevTools!
- created [an issue](https://github.com/microsoft/vscode-docs/issues/5421) on the VS Code documentation repo

### Jun 23, 2022
- started TOP lesson ["Debugging Node"](https://www.theodinproject.com/lessons/nodejs-debugging-node)
- one of the assignments was to read [Node.js debugging in VS Code](https://code.visualstudio.com/docs/nodejs/nodejs-debugging); this was hard and I had to take a step back to start with [Debugging in VS Code](https://code.visualstudio.com/docs/editor/debugging) first
- learned how to configure a launch.json file
- in VS Code, the two core debugging modes _Launch_ and _Attach_ handle two different workflows: "think of a **launch** configuration as a recipe for how to start your app in debug mode before VS Code attaches to it, while an **attach** configuration is a recipe for how to connect VS Code's debugger to an app or process that's already running"_
- glob patterns specify sets of filenames with wildcard characters
- a wildcard character is a kind of placeholder represented by a single character [...] which can be interpreted as a number of literal characters or an empty string. It is often used in file searches so the full name need not be typed.
- learned more about IntelliSense, breakpoints and logpoints
- REPL stands for Read-Eval-Print Loop
- reviewed three array methods (.at(), .concat() and .copyWithin()) and documented them in my dedicated GH repo
- 🎂 webdev-learning anniversary! it's been exactly one year since i started my coding journey with The Odin Project.

### Jun 22, 2022
- Finished [Traversy Media's Node.js Crash Course video](https://www.youtube.com/watch?v=fBNz5xF-Kx4), notably reviewed the URL, Event, EventEmitter and HTTP modules and learned how to deploy an app to Heroku
- My Honeypot application got denied because they only offer onsite positions in Germany, Austria, Switzerland and The Netherlands at the moment (I specified my wish to remain in France on my profile)
- Applied for a 10-weeks bootcamp I had been eyeing for a while: took their technical test, updated my CV and scheduled an interview. Crossing fingers!
- Completed 30% of Codecademy's [JavaScript track](https://www.codecademy.com/learn/introduction-to-javascript). Reviewing the very fundamentals of JavaScript with a different learning material / from a different perspective was refreshing and helped clarifying some concepts!

### Jun 21, 2022
Reviewed TOP *Introduction to Node* and finished the mandatory assignments from *Getting Started*.

### Jun 20, 2022
Kept working on TOP [Getting Started](https://www.theodinproject.com/lessons/nodejs-getting-started) lesson. Learned how to build an HTTP server, how to make HTTP requests with Node (notably with the Axios library), usages of the fs module including fs.writeFile() and fs.readFile(). Fireship's video [Node.js Ultimate Beginner’s Guide in 7 Easy Steps](https://youtu.be/ENrzD9HAZK4) helped a lot. Created a profile on Honeypot.

### Jun 19, 2022
Tried practicing Next.js, but Node.js knowledge seemed to be required / help a lot for most challenges I encountered so I kept working on the Node.js documentation.

### Jun 18, 2022
Still coding along the Node.js documentation these past days, will get back into coding "real projects" the upcoming week!

### Jun 15, 2022
Finally started TOP NodeJS course! Completed [Introduction: What is NodeJs](https://www.theodinproject.com/lessons/nodejs-introduction-what-is-nodejs) and started [Getting Started](https://www.theodinproject.com/lessons/nodejs-getting-started). Bridging the gap between the MDN introductory articles and the code-alongs from the Node.js documentation has been tough so far.

## Before starting Node.js

Jun 14, 2022 — Day 3, finished the Next.js tutorial and deployed my blog (hosted in a private GitHub repo) to Vercel! The workflow reminds me of my early coding days building a Hugo website and deploying it to Netlify. Learning Next.js really is challenging me, and despite it being intended for programmers who shouldn't need anything more than basic JS/React.js knowledge, I've found myself having to search for explanations as to Node.js/backend queries... This was daunting at first, but ended up being do interesting! I'm very curious and motivated to learn about the backend now.

Jun 13, 2022 — Day 2 going through the Next.js tutorial.

Jun 12, 2022 — Worked through the [Next.js official tutorial](https://nextjs.org/learn/basics/create-nextjs-app): completed the sections "Create a Next.js app", "Navigate between Pages" and "Assets, Metadata and CSS". So far, the learning curve does not look as steep as that of going from vanilla JS to React.js, but learning a new framework (as light as it is) still is tedious!

Jun 11, 2022 — Decided to keep my personal website as a simple React.js rather than a Next.js app as it is a SPA. Read the Next.js documentation still.

Jun 10, 2022 — Submitted a PR to fix an issue (lesson minor restructuring) on TOP curriculum repo.

Jun 9, 2022 — Been committing progress about my Notion clone directly on the corresponding repo the past days. Started building my personal website with React.js and Next.js in private today.

June 3, 2022 — Kept working on my Notion clone, dived deeper into the differences between getBy, queryBy and findBy in Testing Library and starting writing a Medium article about it. Re-read the React documentation on conditional rendering and implemented it in the Nav component of my Notion clone. Currently trying to write a groupBy function that would take an array and a key as arguments and split the array into several ones based on their values of the key that was passed. Watched [this video from Splain Train](https://www.youtube.com/watch?v=iBGUyPwm_dM), came across [this article from Dmitri Pavlutin](https://dmitripavlutin.com/javascript-array-group/) and discovered [the array grouping proposal](https://github.com/tc39/proposal-array-grouping) from TC39.

June 2, 2022 — Started building a Notion clone with React.js, forcing myself to use TDD. Thought I was having troubles with .map() nesting in the return() of my Nav component: the first map aimed to display my navbar's links, and the second map aimed to display their respective sublinks. For some reason, my code would break. Turns out the issue was, that one of the links had no sublinks (I was trying to map a property that not every array item had). Will have to look up conditional rendering tomorrow!

## May 2022 (from oldest to newest)
May 1, 2022 — Changed the deck randomization's dependency (it was previously looking for a currentCard state change; now it depends on a clickCounter state change) and added a currentScore and a highScore features.  

May 2, 2022 — Completed the Memory Card project; merged Deck and Main into a single Main component, fixed updateScore() function, mentored my study partner on JavaScript promises.  

May 3, 2022 — Reviewed [ESLint and Prettier usage for React apps created with create-react-app](https://www.youtube.com/watch?v=bfyI9yl3qfE), studied [The Odin Project section on *async* and *await*](https://www.theodinproject.com/lessons/node-path-javascript-async-and-await).  

May 4, 2022 — Started [TOP section on testing](https://www.theodinproject.com/lessons/node-path-javascript-testing-basics) with Jest; notably watched Fun Fun Function's videos on that matter and read/practiced the sections "Getting started" and "Using matchers" from the Jest documentation. Started the [Testing Practice](https://www.theodinproject.com/lessons/node-path-javascript-testing-practice) project by adding a "capitalize" and a "reverseString" functions / tests. Installed Quokka.

May 5, 2022 — Finished reverseString and calculator, started caesarCipher.

May 6, 2022 — Worked on caesarCipher.

May 7, 2022 — Finished caesarCipher and analyzeArray.

May 8, 2022 — Watched Fun Fun Function's ["Mocking basics" and "Mocking continued" videos](https://www.youtube.com/watch?v=3PjdxjWK0F0&list=PL0zVEGEvSaeF_zoW9o66wa_UCNE3a7BEr&index=4), read [Why I use Tape Instead of Mocha & So Should You](https://medium.com/javascript-scene/why-i-use-tape-instead-of-mocha-so-should-you-6aa105d8eaf4) by Eric Elliott, tried out a TOP student [battleship live demo](https://benders-battleship.netlify.app/), initialized my [Shopping Cart](https://www.theodinproject.com/lessons/node-path-javascript-shopping-cart) project, watched [Joe Webb's video on learning to code with ADHD](https://youtu.be/GOQI8Mn9RCk) read [TOP's section "React Testing Part 1](https://www.theodinproject.com/lessons/node-path-javascript-react-testing-part-1), read the [Testing Library queries documentation](https://testing-library.com/docs/queries/about/).  

May 9, 2022 — Read React Testing Library's cheatsheet, watched [Leigh Halliday's introduction to React Testing Library](https://www.youtube.com/watch?v=YQLn7ycfzEo&t=0).  

May 10, 2022 — Read TOP section on [React Router](https://www.theodinproject.com/lessons/node-path-javascript-router) and read the [documentation overview](https://reactrouter.com/docs/en/v6/getting-started/overview).

May 11, 2022 — Completed TOP section on React Router and ES6. Started working on a new portfolio but npm start would weirdly launch webpack instead of react-scripts, there might have been an issue with the dependencies. Haven't coded in a while.

May 13, 2022 — Reviewed TOP section on asynchronous code (callbacks, promises) as well as how to set up a React app without create-react-app.

May 16, 2022 — Started working on my portfolio.

May 17, 2022 — Watched Eddie Jaoude's [complete guide to open source](https://www.youtube.com/watch?v=yzeVMecydCE).

May 21, 2022 — Styled my portfolio's UI.

May 26, 2022 — Getting back into the swing of things! Read and coded along TOP lesson *[React Testing Part 2](https://www.theodinproject.com/lessons/node-path-javascript-react-testing-part-2)* and opened [my first PR](https://github.com/TheOdinProject/curriculum/pull/24163) on The Odin Project's curriculum for typos fixes. Watching SuperSimpleDev's video on [how to become a software engineer](https://www.youtube.com/watch?v=h-grthPvpB0) rekindled my motivation in this self-taught marathon.

May 27, 2022 — Read more about React testing and started learning what can be done Firebase. Had my PR from yesterday successfully merged! Submitted [another PR](https://github.com/mdn/translated-content/pull/5861) to fix some broken links on MDN's French version; found this opportunity to contribute as I was looking into the MDN repo open issues. Listened to CodeNewbie's episode "Why ethics and contributor behavior matters in open source" with Coraline Ada Ehmke. Tomorrow I'd like to complete the [Firebase web codelab](https://firebase.google.com/codelabs/firebase-web), finish watching Eddie Jaoude's [complete guide to open source](https://www.youtube.com/watch?v=yzeVMecydCE), and start designing my next project / contribute to more open source projects. Feeling optimistic! Social coding is such a booster!

May 28, 2022 — Started the Firebase codelab.

May 30, 2022 — Continued the Firebase codelab, curiously my Google name and avatar would display neither within the sandbox nor within the completed version. Messages were successfully stored in the Firestore, but again the UI wouldn't update. Trying to fix that!

May 31, 2022 — Completed the Firebase codelab without succeeding in replicating the expected behaviour sadly. Moving on!

## April 2022 (from oldest to newest)
April 25, 2022 — Read the sections 3 (Using the State Hook) and 4 (Using the Effect Hook) from the React Hooks documentation.

April 26, 2022 — Read the sections 5 (Rules of Hooks) and 6 (Building Your Own Hooks) from the React Hooks documentation.

April 27, 2022 — Skimmed through the sections 7 (Hooks API Reference) and 8 (Hooks FAQ) from the React Hooks documentation + before refactoring the Deck component from my Memory Card project by extracting a "cards" array into its own custom hook. Separating concerns helps making files simpler and shorter, and thereby, code cleaner.

April 28, 2022 — Worked on my Memory Card project: added a function that randomizes the order of an array's items, styled the UI, and added an event listener to the Cards so their value can be stored in the Deck's state. Things I had to look up: what's new with React 18, difference between e.target and e.currentTarget. Next: read the Hooks API documentation properly + find how to deal with the fact that useState is async (useCallback?).

April 29, 2022 — Added deck randomization on each render to my Memory Card project and read the React documentation on the useCallback, useMemo and useRef hooks.
