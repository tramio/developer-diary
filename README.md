# Developer diary 🟩

April 25, 2022 — Read the sections 3 (Using the State Hook) and 4 (Using the Effect Hook) from the React Hooks documentation.

April 26, 2022 — Read the sections 5 (Rules of Hooks) and 6 (Building Your Own Hooks) from the React Hooks documentation.

April 27, 2022 — Skimmed through the sections 7 (Hooks API Reference) and 8 (Hooks FAQ) from the React Hooks documentation + before refactoring the Deck component from my Memory Card project by extracting a "cards" array into its own custom hook. Separating concerns helps making files simpler and shorter, and thereby, code cleaner.

April 28, 2022 — Worked on my Memory Card project: added a function that randomizes the order of an array's items, styled the UI, and added an event listener to the Cards so their value can be stored in the Deck's state. Things I had to look up: what's new with React 18, difference between e.target and e.currentTarget. Next: read the Hooks API documentation properly + find how to deal with the fact that useState is async (useCallback?).

April 29, 2022 — Added deck randomization on each render to my Memory Card project and read the React documentation on the useCallback, useMemo and useRef hooks.

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

June 2, 2022 — Started building a Notion clone with React.js, forcing myself to use TDD. Thought I was having troubles with .map() nesting in the return() of my Nav component: the first map aimed to display my navbar's links, and the second map aimed to display their respective sublinks. For some reason, my code would break. Turns out the issue was, that one of the links had no sublinks (I was trying to map a property that not every array item had). Will have to look up conditional rendering tomorrow!

June 3, 2022 — Kept working on my Notion clone, dived deeper into the differences between getBy, queryBy and findBy in Testing Library and starting writing a Medium article about it. Re-read the React documentation on conditional rendering and implemented it in the Nav component of my Notion clone. Currently trying to write a groupBy function that would take an array and a key as arguments and split the array into several ones based on their values of the key that was passed. Watched [this video from Splain Train](https://www.youtube.com/watch?v=iBGUyPwm_dM), came across [this article from Dmitri Pavlutin](https://dmitripavlutin.com/javascript-array-group/) and discovered [the array grouping proposal](https://github.com/tc39/proposal-array-grouping) from TC39.

Jun 9, 2022 — Been committing progress about my Notion clone directly on the corresponding repo the past days. Started building my personal website with React.js and Next.js in private today.

Jun 10, 2022 — Submitted a PR to fix an issue (lesson minor restructuring) on TOP curriculum repo.

Jun 11, 2022 — Decided to keep my personal website as a simple React.js rather than a Next.js app as it is a SPA. Read the Next.js documentation still.

Jun 12, 2022 — Worked through the [Next.js official tutorial](https://nextjs.org/learn/basics/create-nextjs-app): completed the sections "Create a Next.js app", "Navigate between Pages" and "Assets, Metadata and CSS". So far, the learning curve does not look as steep as that of going from vanilla JS to React.js, but learning a new framework (as light as it is) still is tedious!

Jun 13, 2022 — Day 2 going through the Next.js tutorial.

Jun 14, 2022 — Day 3, finished the Next.js tutorial and deployed my blog (hosted in a private GitHub repo) to Vercel! The workflow reminds me of my early coding days building a Hugo website and deploying it to Netlify. Learning Next.js really is challenging me, and despite it being intended for programmers who shouldn't need anything more than basic JS/React.js knowledge, I've found myself having to search for explanations as to Node.js/backend queries... This was daunting at first, but ended up being do interesting! I'm very curious and motivated to learn about the backend now.

Jun 15, 2022 — Finally started TOP NodeJS course! Completed [Introduction: What is NodeJs](https://www.theodinproject.com/lessons/nodejs-introduction-what-is-nodejs) and started [Getting Started](https://www.theodinproject.com/lessons/nodejs-getting-started). Bridging the gap between the MDN introductory articles and the code-alongs from the Node.js documentation has been tough so far.
