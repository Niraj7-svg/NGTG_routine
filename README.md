# NGTG Skill Timetable

A personal study and skill-building tracker for a structured weekly routine focused on motion design, editing, portfolio work, and creative practice.

## Overview

This project is a single-page HTML timetable that helps you:

- plan weekly learning and practice blocks
- track daily completion progress
- log portfolio targets and milestone achievements
- maintain a streak-based habit system
- review progress with a lightweight local dashboard

It is designed around a daily rhythm with work blocks for learning, practice, creation, portfolio output, and weekly review.

## File

- `NGTG Skill Timetable.html` — the complete interactive timetable and tracker

## Features

- Weekly day-by-day schedule for different skill tracks
- Daily task checklist with completion tracking
- Portfolio target counters and progress bars
- Milestone system with unlock rewards
- Streak tracking for productive days
- Theme toggle support for light/dark display
- Local browser persistence using `localStorage`
- No setup or installation required

## How to use it

1. Open `NGTG Skill Timetable.html` in a browser.
2. Select a day from the top tabs to view that day's tasks.
3. Check off completed blocks as you finish them.
4. Update portfolio progress goals using the counters.
5. Reset progress only when you intentionally want to clear saved local state.

## Notes

- Progress is saved in the browser, so it persists across refreshes on the same device/browser.
- The timetable is intentionally designed as a personal system rather than a generic app; you can edit the schedule inside the HTML file to fit your own routine.
- The rules and milestones are embedded in the page as part of the planning system.

## Suggested customization

If you want to adapt this for your own workflow, edit the `DAYS` and `TR` arrays in the script section of the HTML file:

- `DAYS` defines each weekday's focus and task blocks
- `TR` defines portfolio target categories and required counts

## License

This project is intended for personal use.
