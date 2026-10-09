# Hours
For calculating hours
Hours

A small personal app for tracking all 24 hours of the day. It’s a single HTML file with no frameworks, no build step and no backend. It installs on a phone’s home screen like an app.

What it does
24-hour ring: the thick outer ring is what you actually did, and the thin inner ring is your planned day. A needle shows the current time.
One-tap tracking: tap Deep work, Learning, Reading, Gym, Extra work, College, Nap, Sleep, Wasted or Other. A live timer runs until you switch.
Plan check: shows what your plan says for right now, and flags it when you’re doing something else.
Daily targets: a minimum for each activity (like 3h of deep work) and a maximum for wasted time.
Missed blocks: add a block later, or go back and fix earlier days.
Untracked time: shows how many hours you haven’t accounted for.
Week view: hours per activity over 7 days, and how many days you hit your deep-work target.
Backup and restore: export your data as a JSON file.
Tech

Plain HTML, CSS and JavaScript in one file, with the data saved in the browser’s localStorage. The ring is drawn with inline SVG. It works offline once opened and follows your phone’s light or dark theme.

Install on Android

Open the page in Chrome, tap ⋮, then Add to Home screen.

Why

Everyone gets the same 24 hours. This app makes it hard to lose them without noticing.
