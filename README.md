# AIxID - i want to be there

A 15-minute talk by Luka Or (Haifa, 3.11.26), converted from `Luka or_AIxID_e.pptx` to one HTML page. Slides 13-14 (photos) were added after Level 1, so from there on slide numbers are 2 higher than in the pptx.

Open `index.html` in Chrome (works offline), press **F** for full screen.

- Next: → / ↓ / PageDown / Space / Enter / click. Back: ← / ↑ / PageUp.
- Slide 2 waits: the first press draws the rings around you, are, here, one by one, overlapping, in about 1.1 seconds (`draw` and `stagger` in the `here` object; before: 550 ms each with no overlap, 2 seconds), and the next moves on.
- Slide 3 draws itself on arrival: "how" is already there, then each line leads to the next word, in about 2 seconds. A press mid-way completes it, the next moves on. `speed` (was 3.2), `wordIn` (was 120) and `start` (was 300) in the `sentence` object set the pace.
- Slide 5: "Specialization is for insects." enters word by word on arrival, 110 ms apart. Slide 8: on arrival the strike draws left to right, then "the process" writes itself letter by letter, 38 ms apart. Both timings are in the `reveal` lines.
- Slide 10 starts with no arrows. The first press draws the short black arrow, the second the long one, black, a 0.2 second pause, then orange; each stays. The next moves on. Timings are in `presses` in the `trajectory` object.
- Slide 12 (Level 1) draws its arrow on arrival: black, a 0.2 second pause, then orange. Timings are in `steps` in the `level1` object.
- Slide 16 (slide 14 in the pptx) starts with "It's all about you". Presses show "It's not magic" and "S#@IT in S#@IT out" with no animation, the next draws the arrow right to left, and the next moves on. Its text is drawn as shapes (Helvetica Neue outlines), so it looks the same on any computer.
- Slide 22 (Level 2, slide 20 in the pptx) starts with only the box and crank. On arrival the crank turns once, then the spring pops out with the plate on top, overshoots and settles. `turn`, `bounce` and `damping` in the `jack` object set the feel.
- Slide 23 (21 in the pptx): on arrival the arrow draws left to right, then the dot appears. Slide 24 (22 in the pptx) starts with "Building Our Own Tools for Design"; the first press changes it to "Social Project Based Learning", the next moves on.
- Slide 25 loops silently on its own. Slide 27 waits: the first press plays the film with sound, the next moves on.
- Links on slides 25, 28 and 29 open in a new tab and need internet. On 28 and 29 a click on an image opens its link too, so on 28, where the image fills the slide, move on with the keyboard or clicker. Closing the tab returns to the same slide; full screen may need F again.
- `#N` in the address opens slide N.

`assets/` holds the deck's original images and videos. The film on slide 27 comes from the copy embedded in the pptx, not a YouTube stream; it was re-encoded (keyframe every 2 seconds, no B-frames) after one report of audio playing over a frozen first frame, which did not reproduce in testing.
