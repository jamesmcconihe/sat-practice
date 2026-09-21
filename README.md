# SAT Practice Lab

A free, self-contained SAT practice tool. Open it in any browser. No login, no install, nothing to download.

**Live site:** https://jamesmcconihe.github.io/sat-practice/

## What it does

- 88 practice questions in digital SAT format: 44 Math, 44 Reading and Writing
- Four difficulty levels: Foundation, Steady, Build, and Stretch
- Every question shows the correct answer plus numbered, step-by-step reasoning and a takeaway rule
- 62 flip cards covering math formulas, shortcuts, grammar rules, vocabulary, and test strategy
- **What You Keep Missing** mode, which builds a drill from only the questions you have gotten wrong
- Progress saved between sessions, including total accuracy and best practice band
- A 20-question mini test with three pacing options: no timer, standard pace, or time and a half
- A practice score band that shows which direction the scores are moving

## Accessibility

- Read aloud for questions, answer choices, and explanations, using the browser's built-in speech
- Three text sizes
- Wide-spaced font option
- High contrast mode
- Full keyboard control: number keys 1 to 4 select an answer, Enter checks it, N moves to the next question, arrow keys move between flashcards
- Screen reader friendly, with proper roles and live announcements
- Respects the operating system's reduced motion setting

## Saved progress

Progress is stored in the browser using localStorage. It never leaves the device and is not sent anywhere. Each browser and each device keeps its own record. "Clear saved progress" on the home screen wipes it.

## Technical notes

Everything lives in a single `index.html` file. No frameworks, no build step, no dependencies, no external requests. To change a question, open the file in a text editor and edit the `Q` array near the top of the script section. Each entry has a section, a level from 1 to 4, the question, four choices, the index of the correct answer, the explanation steps, and a takeaway tip.

## About the questions

These questions were written to match the format and skills of the digital SAT. They are practice material and are not official College Board questions. For official full-length adaptive practice, use the free Bluebook app and Official Digital SAT Prep on Khan Academy.

## License

Free to use, copy, and modify.
