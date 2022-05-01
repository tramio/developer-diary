# Developer diary 🟩

April 25, 2022 — Today I read the sections 3 (Using the State Hook) and 4 (Using the Effect Hook) from the React Hooks documentation.

April 26, 2022 — Today I read the sections 5 (Rules of Hooks) and 6 (Building Your Own Hooks) from the React Hooks documentation.

April 27, 2022 — Today I skimmed through the sections 7 (Hooks API Reference) and 8 (Hooks FAQ) from the React Hooks documentation + before refactoring the Deck component from my Memory Card project by extracting a "cards" array into its own custom hook. Separating concerns helps making files simpler and shorter, and thereby, code cleaner.

April 28, 2022 — Today I worked on my Memory Card project: added a function that randomizes the order of an array's items, styled the UI, and added an event listener to the Cards so their value can be stored in the Deck's state. Things I had to look up: what's new with React 18, difference between e.target and e.currentTarget. Next: read the Hooks API documentation properly + find how to deal with the fact that useState is async (useCallback?).

April 29, 2022 — Today I added deck randomization on each render to my Memory Card project and read the React documentation on the useCallback, useMemo and useRef hooks.

May 1, 2022 — Today I changed the deck randomization's dependency (it was previously looking for a currentCard state change; now it depends on a clickCounter state change) and added a currentScore and a highScore features.
