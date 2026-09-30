# Clock

Analog and digital clocks drawn on a single HTML canvas, using the browser's current time.

## What it does
- Redraws roughly continuously from `new Date()`.
- Two digital readouts of the current time in 12-hour format with AM/PM, a blinking colon, and a milliseconds counter. The digits are drawn from hand-built pixel-grid patterns (the `clockNumber_*` arrays at the top of `Clock.js`).
- An analog clock face with numbers 1-12, hour dots, and hour / minute / second hands.
- The analog face is written to draw an image (`mickeymouse.gif`) near the clock face. That image is **not included** in this repo, so that spot will be empty unless you add an image with that file name.

## Run it
Open `Clock.html` in a browser. No build step or server needed.

## Files
- `Clock.html` - a 1500x700 canvas that loads the script
- `Clock.js` - all drawing and timing logic
