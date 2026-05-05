# Stopwatch App

A stopwatch web app built with vanilla JavaScript. Tracks time down to the millisecond, supports lap recording, and shows you which lap was your fastest and slowest in real time.

Built this to get comfortable with `requestAnimationFrame` for smooth time display — `setInterval` drifts over time, RAF doesn't.

## What's in it

- Start, pause, resume, and reset controls
- Lap time recording with a running split log
- Best and worst lap highlighted automatically (green / red)
- Per-lap delta — shows how much faster or slower each lap was compared to the previous one
- Animated SVG progress ring that tracks the current 60-second cycle
- Time accurate to the millisecond using `Date.now()` and `requestAnimationFrame`

## Tech

HTML · CSS · JavaScript (no dependencies)

## Live demo



## Running locally

Open `index.html` in a browser. That's it.

---

Made by [Aditya Srivastava](https://github.com/adi-codeartist001)
