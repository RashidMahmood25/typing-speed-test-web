# Typing Speed Test (Web)

A single-page typing speed test. Type the passage shown and get your live
WPM and accuracy; when the test ends you get a final result, your best WPM,
and a short history of recent results.

## Features

- **Test lengths:** 30 seconds, 60 seconds, 2 minutes, or the full passage
- **Live feedback:** each character turns green (correct) or red (wrong) as
  you type, with the current character highlighted
- **Live stats:** WPM and accuracy update while you type
- **Best score + history:** best WPM and the last 5 results are saved in your
  browser (localStorage) — nothing leaves your device
- **New passage / Restart** buttons; pasting is disabled so the test stays fair

WPM is calculated the standard way: (correct characters ÷ 5) ÷ minutes.

## How to use

Open `index.html` in any modern browser (double-click the file, or serve the
folder with any static server). Click the typing box and start typing — the
timer starts on your first keystroke. No build step, no dependencies.

## What was practiced

- Single self-contained HTML/CSS/JS page
- Live per-character rendering from a typed string
- Timers (`setInterval`), elapsed-time math, and the standard WPM formula
- localStorage for best score and recent-results history
