# Intervalos de Uníssono

A browser trainer for singing unison intervals. The piano plays a note twice in one bar, you sing the same note in the next bar, and the app shows if you are in tune.

**Open it:** https://luizvarela.github.io/unison-trainer/

- Uses the 28 notes of exercise #12 from the "Intervalos de unísono" video (same order, octaves and 108 bpm), or shuffled, random or your own notes.
- Draws your pitch live on the staff and grades each half note in cents. Any octave counts by default.
- Runs entirely in the browser: Web Audio for the piano and YIN pitch detection on the microphone. Nothing is recorded or uploaded.

Use headphones so the microphone only hears your voice.

## Run locally

```sh
python3 -m http.server 8765
```

Then open http://127.0.0.1:8765/. The microphone works only on `localhost` or `https`.

Optional: put a `piano.m4a` next to `index.html` with the video's audio and the app plays the recorded piano instead of the synth. It is ignored by git.
