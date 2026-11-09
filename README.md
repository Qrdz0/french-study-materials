# Frans Examen Flashcards

A lightweight, single-file flashcard application built to help study for the French exam. It runs entirely in the browser without any external dependencies and can be hosted for free on GitHub Pages.

## Features

- 3D flip animations for revealing answers.
- Clean, dark-mode user interface.
- Progress tracking to show which card you are on.
- Navigation buttons to move forward and backward.
- Mobile-friendly design, so it can be used on a phone while studying.

## How to Use

1. Open the website.
2. Click on the card to flip it and reveal the answer.
3. Use the Previous and Next buttons at the bottom to navigate through the deck.

## How to Add New Flashcards

All the study material is stored in a JavaScript array inside the `index.html` file. To add new words or sentences:

1. Open `index.html` in a text editor.
2. Scroll down to the script section at the bottom.
3. Find the `flashcards` array.
4. Add a new line with the question and answer format:

```javascript
{ front: "Je m'appelle...", back: "My name is..." },
