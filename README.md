# Frans Examen Flashcards

A lightweight, single-file flashcard application built to study for the French exam (Klas 3-4 ORLO / ZOWE). It runs entirely in the browser without any external dependencies and can be hosted for free on GitHub Pages.

## Exam Coverage

This flashcard deck is built directly from the official study guide and covers:

- **Grammar:** Subject pronouns, the irregular verbs Être and Avoir, and regular verbs ending in -ER.
- **Tricky Verbs:** The specific spelling rules for -GER verbs (nous mangeons) and -CER verbs (nous commençons).
- **Vocabulary:** Classroom expressions, introducing yourself, introducing someone else, and talking about hobbies (loisirs).
- **Numbers:** 0 to 1000.
- **Spelling:** The pronunciation rules for the letters C and G depending on the vowels that follow them.

## Features

- 3D flip animations for revealing answers.
- Clean, dark-mode user interface.
- Progress tracking to show which card you are on out of the total.
- Navigation buttons to move forward and backward.
- Mobile-friendly design.

## How to Use

1. Open the website.
2. Click on the card to flip it and reveal the answer.
3. Use the Previous and Next buttons at the bottom to navigate through the deck.

## How to Add New Flashcards

All the study material is stored in a JavaScript array inside the `index.html` file. To add new words or sentences when studying:

1. Open `index.html` in a text editor.
2. Scroll down to the script section at the bottom.
3. Find the `flashcards` array.
4. Add a new line with the question and answer format:

```javascript
{ front: "Je m'appelle...", back: "My name is..." },
