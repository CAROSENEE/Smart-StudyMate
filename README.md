# Smart-StudyMate

**Smart Student Assistant** — a friendly mobile UI prototype that helps university students organize classes, study sessions, assignments, and progress.

<p align="center">
  <img src="smart_studymate_logo_transparent.png" alt="Smart StudyMate logo" width="260">
</p>

## Overview

Smart-StudyMate brings everyday student tools together in one simple dashboard. This repository contains an interactive front-end prototype designed around a 390 × 844 mobile screen, with an indigo-and-white interface, rounded cards, and the Inter font family.

## Features

### Student experience

- Demo login with password error, loading, and welcome states
- Dashboard with today's classes, assignment deadlines, study goal, water tracker, and AI study suggestion
- Weekly class routine with day tabs, class details, and reminder controls
- Study planner with checkable tasks, revision plan, deadlines, and an add-task flow
- Pomodoro focus timer with 25- and 50-minute modes
- AI suggestion cards for studying, health, and breaks
- Progress view with weekly study hours, attendance, and goal completion
- Profile settings with notification toggles and a logout confirmation dialog

### Admin demo

- Separate admin entry from the login screen
- Overview cards for student enrollment, activity, and progress
- Student list with search, batch filters, and progress/attendance sorting
- Individual student progress details, reports, and admin settings

## Run the prototype

No package installation or build step is required.

1. Download or clone this repository.
2. Open `figma.html` in a modern web browser.
3. Use the pre-filled student email and enter any password except `wrong` to see the successful demo login. Enter `wrong` (or leave the field empty) to see the error state.
4. Select **Admin login · demo access** on the login screen to explore the admin prototype.

## Project structure

```text
.
├── README.md
├── figma.html                       # Interactive UI prototype
└── smart_studymate_logo_transparent.png  # App logo
```

## Notes

This is a front-end UI prototype. Login, student records, reports, and other content use sample/demo data; there is no connected authentication service, database, or live AI backend. Google Fonts is used to load Inter when an internet connection is available, with a system font fallback.

## License

No license has been added yet. Add a `LICENSE` file before reusing or distributing this project under specific terms.
