# Review — Satu saat di Bumi

## Gates

- `hyperframes check`: passed (lint, runtime, layout, contrast, craft, audio). One lint warning remains: `gsap_repeated_fromto_without_baseline` in `tally.html`. It is a false positive: the three count-ups each tween their own counter object, and the linter cannot tell them apart.
- Seam gate (`motion-doctrine/scripts/seam-gate.mjs verify`): 9/9 seams PASS, 0 warnings.

## Fixed after the first snapshot pass

- The tally list was blank. Its clip-path wrapper had zero height, so it is now full-frame.
- A sun ray crossed "juta tan". The disc moved 80 px right.
- The ECG trace crossed the closing line. The line moved below the trace and the source moved under the label.
- The "1" in the hook was off-centre in its ring.
- `#sun-label` and `#sun-more` overlapped, and so did `#tally-end` and `#tally-next`.
- Dead stretch at 46–49.6 s. Added "— dan yang itu pun dah berlalu."

## Known limits

- No music bed: HeyGen is not connected and there is no local music model. Sound is the bundled Pixabay SFX only (whooshes on cuts, pops and pings on landings, bass hits on the sun and the heart, riser into the last line). Levels are measured, not heard.
- Numbers are rounded and marked ≈ where they are estimates. Every number has its source on screen (see SPEC.md).
