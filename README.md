# Energy Planner

A to-do list that reorders itself to match how you feel right now.

**Try it live:** https://isabelleromero99.github.io/energy-planner/index.html

![Energy Planner screenshot](screenshot.png)
)

## The problem
Most to-do lists treat every hour of your day the same. But the hardest task
at 4 pm when you're exhausted is not the same as at 10 am when you're sharp.
Energy Planner asks how you feel and puts the right tasks first.

## How it works
Every task has a difficulty (easy, medium, hard). Every energy level has a
target: Tired starts with easy tasks, Okay with medium, Sharp with hard.
Tasks closest to your target go first; finished tasks sink to the bottom.
Ties are broken by time: shorter first when tired, longer first when sharp.

## Features
- One-tap energy check-in (Tired / Okay / Sharp)
- Tasks reorder with a smooth animation
- Optional time estimates (tasks without one still sort sensibly)
- Emoji for each task
- Saves automatically in your browser, no account needed
- Works on desktop and phone

## How to use it
1. Pick how you feel right now.
2. Add tasks with a difficulty and, if you know it, a time estimate.
3. Work from the top of the list, and switch your energy whenever it changes.

## Built with
HTML, CSS and vanilla JavaScript. Data is stored with localStorage.
No frameworks, no backend.

## AI disclosure
I used Claude (an AI assistant) to help write the code. 
The idea, design decisions, testing and customization are mine.

## Credits
- Fonts: [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque)
  and [Instrument Sans](https://fonts.google.com/specimen/Instrument+Sans),
  via Google Fonts (open source)

## What's next
- Automatic energy check-ins at set times
- Learning from your history when you tend to be sharp
- Calendar integration

## Author
Isabel Romero, built solo at HackEd [2026].
