# 081 · Desk Reset

A five-minute guided body-and-eye reset you can run without leaving your chair.

Desk Reset walks you through a rotating set of simple seated stretches and a **20-20-20 eye break**, one plain cue at a time, each with a calm countdown. It is about the break itself, not the work interval, so it sits apart from a focus or pomodoro timer. Pick a routine length and it remembers your choice for next time.

## What it does

- Builds a fresh routine each run from a pool of twelve chair-based stretches, always opening with a settle-and-breathe moment and placing one 20-20-20 eye rest in the middle.
- Shows one exercise at a time with a large countdown ring, a plain-language cue, and your progress through the routine.
- Lets you pause, skip, or end at any point.
- Offers 3, 5, or 8 minute lengths, with your last choice persisted.
- Plays an optional soft transition tone between segments, with a mute toggle.

## How to use

1. Choose a routine length: 3, 5, or 8 minutes.
2. Tap **Begin reset** and follow each cue until the countdown ends.
3. When you reach the eye rest, look at something about twenty feet away, soften your gaze, and blink slowly.
4. Finish, then run it again or change the length whenever you like.

Space bar pauses and resumes, the right arrow skips to the next segment.

## Notes

- Single-file vanilla HTML, CSS, and JavaScript. No frameworks, no build step.
- Countdown ring and breathing glow are pure SVG and CSS, so there is no canvas dependency.
- Routine length and mute preference are stored in `localStorage`.
- Honors `prefers-reduced-motion` by stilling the breathing animation.
- Responsive from a 375px phone through desktop.

Part of [AppADay](https://augustineiacopelli.github.io/appaday/), one complete web app shipped every day.
