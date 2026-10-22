# Nursery Etch A Sketch

Nine self-contained family drawing animations for the nursery iPad.

Open https://blampe22.github.io/toy-story-etch-a-sketch/index.html in Safari. Add it to the Home Screen for a standalone display.

Each drawing traces outlines for 72 seconds. The first 35-second shading pass starts at 72 seconds; the second starts at 92 seconds, overlapping by 15 seconds. Drawing finishes at 127 seconds, holds for 15 seconds, and shakes to erase for 2 seconds. The playlist then advances automatically. A full nine-picture loop takes approximately 21 minutes 36 seconds, plus loading time.

Two-finger tap (or double-click on desktop) opens each animation's replay, pause, and duration controls. The playlist waits for the animation's completion message, so pausing or changing its duration does not cut it short. Backgrounding the page pauses the drawing clock.

All images are embedded in their HTML files. Keep index.html and the nine referenced animation files together. Portrait and square images retain their proportions with gray space around them as needed.

The original Roger and Royce proof-of-concept files are retained in the repository for reference and are outside the current playlist.
