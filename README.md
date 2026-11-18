# Florida Sales Associate Review

A study site for the Florida Real Estate Sales Associate pre-license course:
practice exams with answers and explanations, and flashcards for each chapter.

Live at https://nic-tim.github.io/real-estate-/ once GitHub Pages is on
(Settings → Pages → Deploy from a branch → main, / (root)).

## Files

| File | What it is |
|---|---|
| `real-estate/index.html` | The whole site in one file: practice questions (`Q`), flashcard decks (`DECKS`, one per chapter) and the app. |
| `index.html` | Sends the repo's root URL to `real-estate/`. |

No build step and no dependencies. Open `real-estate/index.html` in a browser
to use it locally.

## Adding a chapter

1. Add the chapter's name to `CH` and its number to `CHS`.
2. Add practice questions to `Q` as `[chapter, question, [a, b, c, d], answerIndex, explanation]`.
3. Add a deck to `DECKS` as `[front, back, note]` cards.
