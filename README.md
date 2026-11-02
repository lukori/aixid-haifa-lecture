# AIxID - i want to be there

A 15-minute talk by Luka Or (Haifa, 3.11.26), converted from `Luka or_AIxID_e.pptx` to one HTML page. Slides 13-14 (photos) were added after Level 1, and slide 22 of the pptx was split in two. From slide 14 of the pptx to 21, numbers here are 2 higher. The rest runs: 24 Building Our Own Tools for Design (first half of pptx 22), 25 pptx 26, 26 pptx 27, 27 Social Project Based Learning (second half of pptx 22), 28 pptx 23, 29 pptx 24, 30 pptx 25, 31 pptx 28, 32 pptx 29.

Open `index.html` in Chrome (works offline), press **F** for full screen.

- Next: → / ↓ / PageDown / Space / Enter / click. Back: ← / ↑ / PageUp.
- Slide 1 has the HIT and AIxID logos at the bottom, lined up with the left and right edges of the letter grid, on a shared bottom line.
- Slide 2 waits: the first press draws the rings around you, are, here, one by one, overlapping, in about 1.1 seconds (`draw` and `stagger` in the `here` object; before: 550 ms each with no overlap, 2 seconds), and the next moves on.
- Slide 3 draws itself on arrival: "how" is already there, then each line leads to the next word, in about 1 second. A press mid-way completes it, the next moves on. `speed`, `wordIn` and `start` in the `sentence` object set the pace (2 seconds was 6.4 / 60 / 150; 4 seconds was 3.2 / 120 / 300).
- Slide 5: "Specialization is for insects." enters word by word on arrival, 110 ms apart. Slide 8: on arrival the strike draws left to right, then "the process" writes itself letter by letter, 38 ms apart. Both timings are in the `reveal` lines.
- Slide 10 starts with no arrows. The first press draws the short black arrow, the second the long one, black, a 0.2 second pause, then orange; each stays. The next moves on. Timings are in `presses` in the `trajectory` object.
- Slide 12 (Level 1) is the still illustration with its arrow, no animation. It used to draw the arrow on arrival: 150 ms wait, black 300 ms, 200 ms pause, orange 170 ms, head 70 ms; that version is in the git history, before commit "Slide 12 still".
- Slide 16 (slide 14 in the pptx) starts with "It's all about you". Presses show "It's not magic" and "S#@IT in S#@IT out" with no animation, the next draws the arrow right to left, and the next moves on. Its text is drawn as shapes (Helvetica Neue outlines), so it looks the same on any computer.
- Slide 22 (Level 2, slide 20 in the pptx) starts with only the box and crank. On arrival the crank turns once, then the spring pops out with the plate on top, overshoots and settles. `turn`, `bounce` and `damping` in the `jack` object set the feel.
- Slide 23 (21 in the pptx): on arrival the arrow draws left to right, then the dot appears.
- Slide 28 loops silently on its own. Slide 30 waits: the first press plays the film with sound, the next moves on. Moving the mouse on slide 30 shows a timeline at the bottom: click or drag it to jump, with no effect on the slide count; it hides after 1.5 seconds without movement, so a clicker never shows it.
- Links on slides 25, 26, 28 and 32 open in a new tab and need internet. On 25 and 26 a click on an image opens its link too, so on 25, where the image fills the slide, move on with the keyboard or clicker. Closing the tab returns to the same slide; full screen may need F again.
- Slide 26 (27 in the pptx) has three images with links: AI Photo Studio, Image to Hand Study Sketch and sphericon. The row runs between the left and right margins of the slide, and each caption sits under the left edge of its image.
- `#N` in the address opens slide N.

`assets/` holds the deck's original images and videos. The film on slide 30 comes from the copy embedded in the pptx, not a YouTube stream; it was re-encoded (keyframe every 2 seconds, no B-frames) after one report of audio playing over a frozen first frame, which did not reproduce in testing.
