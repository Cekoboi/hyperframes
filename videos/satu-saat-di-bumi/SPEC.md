# SPEC — Satu saat di Bumi

```text
GOAL:    the viewer feels how much happens in one second, and that the 60 they just spent are gone
OUTPUT:  HyperFrames, 1920 x 1080, 30 fps
TIME:    59 s x 30 = 1770 frames; pacing grid 120 BPM (beat = 15 f, bar = 60 f); every cut on a bar
LOOK:    a printed poster wall: flat colour fields, no gradients, no texture.
         grounds rotate: sun yellow #FFD21F, signal red #FF3B1F, ink #111111, paper #F2EFE8, cobalt #2340FF
         ink is #111111 or #FFFFFF only; yellow is the accent on dark grounds (one word or the number)
         numbers: League Gothic 400, 300-900 px, line-height 0.82, tabular-nums
         lines: Inter 900, 64-96 px, tracking -0.02em; source line Inter 700 28 px at 75% opacity
         depth: none. no shadows, no grain, no vignette. objects are flat cut shapes
OBJECTS: Earth = cobalt disc with two green (#00A86B) land shapes; Sun = yellow disc, cropped by the frame;
         lightning = solid zig-zag bolt; rain = thin white streaks; heart = an ECG trace with one spike;
         baby = round head on a rounded body
MOTION:  enter power4.out / power3.out 0.4 s; counts: the real second runs with ease none over exactly 1.0 s,
         other counts power2.out 1.4 s; stamps back.out(1.6) 0.3 s; text reveals are clip-path wipes, never fades
         seams: cut-the-curve LEFT (current); Z push once (into the facts); UP once (the conclusion)
SHOTS:   0-4    hook    "1" + ring that sweeps for exactly one second -> "Apa yang berlaku di Bumi?"   LEFT
         4-8    ask     "Dalam masa / SATU SAAT / di planet kita…"                                   Z push
         8-14   orbit   Earth runs a 30 km track in 1.0 s, count 0->30 km                            LEFT
         14-20  bolt    44 bolts pop in 1.0 s, count 0->44                                            LEFT
         20-26  rain    streaks fall, count 0->16 juta tan                                            LEFT
         26-32  sun     cropped Sun, 4 juta tan, rays burst                                           LEFT
         32-38  light   red line wraps Earth 7.5 times in 1.0 s, 300,000 km                           LEFT
         38-44  baby    4 babies stamp, 1-2-3-4                                                       LEFT
         44-50  heart   ECG draws for 1.0 s, one spike: "1 degupan jantung anda"                      UP
         50-59  tally   60-second totals count in sequence -> pause -> "Saat itu dah berlalu."
BANNED:  dark void with small floating elements; glow, neon, particles; gradients, glass cards;
         cream + serif + mono labels; everything centred; fade-and-slide-up entries; text moving while read;
         three cards in a row; idle wobble; crossfades; numbers without a source line
QA:      0.0 (thumbnail: "1 SAAT" composed), 1.4 (ring closed), 9.7 (30 km landed), 15.7 (44 bolts),
         27.9 (rays), 33.9 (7½ kali), 39.5 (4 babies), 45.0 (spike), 54.7 (final line), 58.9 (end hold)
```

## Facts (one data module: the numbers below, rounded the same everywhere)

| Fact                           | Value used                                                                          | Source                        |
| ------------------------------ | ----------------------------------------------------------------------------------- | ----------------------------- |
| Earth's orbital speed          | ≈ 30 km/s (29.78), ≈ 107,000 km/h                                                   | NASA                          |
| Lightning flashes worldwide    | ≈ 44 per second, ≈ 1.4 billion a year                                               | NOAA                          |
| Global precipitation           | ≈ 505,000 km³/yr → ≈ 16 million tonnes/s; 2,500 m³ per Olympic pool → ≈ 6,400 pools | USGS (derived)                |
| Sun's mass converted to energy | ≈ 4 million tonnes per second                                                       | NASA                          |
| Speed of light                 | ≈ 300,000 km/s (299,792); Earth's circumference 40,075 km → ≈ 7.5 laps              | physical constant             |
| Births worldwide               | ≈ 4 per second (≈ 132 million a year), ≈ 360,000 a day                              | UN World Population Prospects |
| Resting heart rate             | 60-100 per minute → ≈ 1 per second                                                  | American Heart Association    |
| Totals over 60 s               | 1,800 km; 2,640 flashes; ≈ 250 births                                               | derived from the rows above   |
