# iPAS Cybersecurity Practice System

A browser-based practice system developed to support my preparation for the **iPAS cybersecurity certification examination**.

The system organizes cybersecurity practice questions from multiple examination years and provides randomized quizzes, answer feedback, wrong-answer tracking, and learning history.

## Features

### Randomized Practice

Practice questions are randomly selected from multiple examination years and categories.

The system combines questions from:

- Technical cybersecurity topics
- Information security management topics
- Recent examination years
- Earlier examination years

### Immediate Answer Feedback

After selecting an answer, the system immediately:

- Indicates whether the answer is correct
- Highlights the selected incorrect answer
- Displays the correct answer
- Records the result for later review

### Wrong-Answer Tracking

Incorrectly answered questions are automatically recorded using browser local storage.

The system tracks how many times each question has been answered incorrectly.

Questions answered incorrectly three or more times are identified as frequently missed questions for focused review.

### Adaptive Review

After accumulating practice history across multiple days, previously missed questions can be added back into future practice sessions.

This provides a simple adaptive review mechanism based on the user's previous performance.

### Learning History

The system records:

- Practice date
- Score
- Total number of questions
- Individual answers
- Correct and incorrect responses

Recent practice results can be reviewed directly from the browser.

## Technologies

- HTML5
- CSS3
- JavaScript
- Web Storage API (LocalStorage)

No external framework or backend server is required.

## Repository Structure

```text
iPAS-Cybersecurity-Practice-System/
├── index.html
├── ipas_questions.json
└── README.md
```

## Running the Project

No installation is required.

Clone or download the repository and open:

```text
index.html
```

in a modern web browser.

## Data Storage

Practice history and wrong-answer statistics are stored locally in the browser using `localStorage`.

No personal information or practice records are transmitted to an external server.

## Project Motivation

This project was created as a personal study tool while preparing for the iPAS cybersecurity certification examination.

Instead of reviewing examination questions only as static documents, I developed a browser-based practice interface that supports randomized practice, immediate feedback, repeated-error tracking, and review of previous learning results.

## Future Improvements

Potential extensions include:

- Question filtering by topic
- Performance statistics by cybersecurity domain
- Dedicated wrong-answer review mode
- Progress visualization
- Search and question bookmarking
- Importing question banks from external JSON files
- Responsive interface improvements
- Separation of question data from the application code

## Notes

This project is intended for personal learning and portfolio demonstration.

The current version is a front-end implementation and stores learning records locally in the user's browser.

## Question Bank

The practice questions included in this project were compiled from publicly available iPAS examination materials for personal study purposes.

The quiz interface, question-selection logic, learning-history functions, and wrong-answer tracking mechanisms were implemented as part of this project.