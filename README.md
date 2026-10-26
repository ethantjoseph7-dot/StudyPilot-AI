# StudyPilot AI 📚

StudyPilot AI is a student study dashboard project. It brings simple planning and focus tools together in one website, with the goal of helping students organise their work and practise what they learn.

## Features

The current project includes:

- **Study dashboard** — a summary of tasks and learning progress.
- **Study planner** — add tasks, choose a subject, mark tasks complete, and delete tasks.
- **Progress tracking** — see task completion and saved quiz results.
- **Focus timer** — choose a session length and start, pause, or reset the timer.
- **Practice quiz maker** — paste notes to generate simple practice questions using local text rules.
- **Daily study tips** — display a tip and request another one.

**Important:** The quiz maker is rule-based in this version. It does not connect to an AI model or guarantee that every generated answer choice is good. Review questions and answers before relying on them.

## Screenshots

These screenshots show StudyPilot AI running in a browser.

### Dashboard
![StudyPilot AI dashboard](index.png)

### Study planner
![StudyPilot AI study planner](planner.png)

### Practice quiz generator
![StudyPilot AI quiz generator](quiz.png)

### Learning progress
![StudyPilot AI learning progress](porgess.png)

### Focus timer
![StudyPilot AI focus timer](focus.png)

## Built with

- HTML for page structure
- CSS for layout and responsive styling
- JavaScript for navigation, task management, quiz scoring, and the focus timer
- Browser `localStorage` to keep tasks and quiz history on the same browser

No account or server-side database is included. Saved data is local to the browser and may not follow you to another device or browser.

## Run it locally

1. Download or clone this repository.
2. Open the project folder in VS Code.
3. Open `index.html` in a browser, or use a local development server such as the VS Code Live Server extension.
4. Test the navigation, planner, quiz maker, progress page, and focus timer.

## Live demo

**Live demo URL:** Add the deployed website URL after hosting and testing it. The repository link is not a live demo.

For a static site, GitHub Pages can host the project. Ensure the homepage is named `index.html`, enable Pages in the repository settings, and test the generated URL in a browser.

## Development notes

This project is being developed as a learning project. The current focus is to fix bugs, improve usability, test features, and document how the code works. AI assistance was used during development; code should be reviewed and rewritten by the developer to comply with the competition's AI-use rules.

## Current status

Under development. Before resubmitting, verify that the published site works and make sure the code meets Stardance's AI-use limit.
