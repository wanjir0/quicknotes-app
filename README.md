# quicknotes-app
# Quick Notes

Quick Notes is a small web app for writing short notes and sorting them into Personal, Work and Study categories. You can search your notes, delete them one at a time or all at once, and everything is saved in your browser so your notes are still there after a refresh. It is built with plain HTML, CSS and JavaScript, with no frameworks.

## Features

- Add a note with a category (Personal, Work or Study)
- Each note shows its text, a category label, the date and time it was created, and a Delete button
- Colour-coded note cards, one left-border colour per category
- Validation: empty notes and notes over 200 characters show an error message
- Live, case-insensitive search with a "No notes match your search." message
- Note count that reads correctly for zero, one and many notes
- Notes saved with localStorage so they survive a page refresh
- "Clear all" button with a confirmation prompt (bonus)
- Responsive layout: the form stacks vertically on screens 600px wide or narrower

## How to run locally

1. Clone the repository:
   `git clone https://github.com/wanjr0/quicknotes-app.git`
2. Open the project folder.
3. Double-click `index.html` to open it in your browser (no server or install needed).

## What I learned

- How to build a page with simple HTML (`header`, `main`, `section`, `footer`) and link every `label` to its `input` with `for` and `id`.
- How to lay out a form with Flexbox and use a `@media (max-width: 600px)` rule to change the layout on small/different screens.
- How to keep data in an array of objects and use one `render()` function to rebuild the list.
-  using `createElement` and `textContent` instead of `innerHTML` so user text stays safe.
- How to save and load data with `localStorage`, using `JSON.stringify` and `JSON.parse`.
  
