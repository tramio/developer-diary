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
