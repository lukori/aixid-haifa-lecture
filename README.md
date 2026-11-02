# AIxID - i want to be there

A 15-minute talk by Luka Or (Haifa, 3.11.26), converted from `Luka or_AIxID_e.pptx` to one HTML page. Slides 10-11 were added after the pencil, so from there on slide numbers are 2 higher than in the pptx.

Open `index.html` in Chrome (works offline), press **F** for full screen.

- Next: → / ↓ / PageDown / Space / Enter / click. Back: ← / ↑ / PageUp.
- Slide 2 waits: the first press draws the rings around you, are, here, one by one, overlapping, in about 1.1 seconds (`draw` and `stagger` in the `here` object; before: 550 ms each with no overlap, 2 seconds), and the next moves on.
- Slide 3 draws itself on arrival: "how" is already there, then each line leads to the next word, in about 2 seconds. A press mid-way completes it, the next moves on. `speed` (was 3.2), `wordIn` (was 120) and `start` (was 300) in the `sentence` object set the pace.
- Slide 5: "Specialization is for insects." enters word by word on arrival, 110 ms apart. Slide 8: on arrival the strike draws left to right, then "the process" writes itself letter by letter, 38 ms apart. Both timings are in the `reveal` lines.
- Slide 12 starts with no arrows. The first press draws the short black arrow, the second the long one, black then orange; each stays. The next moves on. Timings are in `presses` in the `trajectory` object.
- Slide 25 loops silently on its own. Slide 27 waits: the first press plays the film with sound, the next moves on.
- Links on slides 25, 28 and 29 open in a new tab and need internet.
- `#N` in the address opens slide N.

`assets/` holds the deck's original images and videos. The film on slide 27 is the copy embedded in the pptx, not a YouTube stream.
