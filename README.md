# Food Science Exam Simulator

A study tool for the food science exam that runs in any web browser, on a phone or a computer. It is a single file, `index.html`: download it and open it. Nothing to install, no sign-in, and nothing is sent anywhere.

## How to use it

1. Download `index.html` (on GitHub: open the file, then **Download raw file**).
2. Double-click it, or open it in Chrome, Safari, Edge or Firefox. On a phone, open it from your Files/Downloads app.
3. Pick a mode for Exam 1:
   - **Mode 1, Answer mode:** every answer is shown right away. Good for first-pass studying.
   - **Mode 2, Simulation mode:** answer each question, then see whether you were right, with the explanation. You get a score and a list of what you missed at the end, with a button to retry only the missed ones.
4. Pick a question type.

The page looks best online (it loads two web fonts) but works fully offline too.

## Question types (Exam 1)

| Type | What it covers |
| --- | --- |
| Key-term matching | All 109 key terms, in sets of 4. The sets are reshuffled every round, and each round covers every term in scope. |
| True / false | The 12 review-guide statements, extra statements on key facts and concepts, plus random "does this definition match the term?" checks. |
| Multiple choice | The review-guide multiple-choice and recall questions, plus extra concept and key-figure questions. |
| Scenarios | Apply a key term to a real situation, for every chapter. |
| Fill in the blank | Review-guide blanks, key facts and figures, and "name the key term" recall. Spelling is checked loosely, and you can count an answer as right if the checker missed it. |
| Short answer | All 10 short-answer questions, each with a model answer and a checklist of key points to include. Tick the points you covered to self-score out of 10. |
| Full practice exam | 2 matching sets, 10 true/false, 10 multiple choice, 5 fill-in and 3 short answers, drawn at random. |

Filters on the question-type screen let you study one chapter, only key facts and figures, or only the questions that come straight from the review guide, and choose 10, 20 or 30 questions per round.

The **timer** in the top bar is optional. Use it as a stopwatch or a countdown; start and pause it any time. It keeps running while you switch question types.

Everything in the Exam 1 study guide is covered except the presentation article essay.

## Exam 2

Exam 2 shows as "To be updated." To add it, open `index.html` in a text editor, find `const EXAM2` in the script, and fill it in with the same fields as `EXAM1` (key terms, true/false, multiple choice, scenarios, fill in the blank, short answer). The comment block at the top of the script explains each field. Add any new chapter names to `CHAPTERS`, then delete `pending: true`. The home screen will show Exam 2 with its own mode buttons.
