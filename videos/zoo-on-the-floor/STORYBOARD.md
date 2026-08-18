---
compositionId: zoo-on-the-floor
duration_s: 91.12 # == audiomap.audio.duration_sec
canvas: { w: 1920, h: 1080, fps: 30 }
style:
  font: "Barlow / IBM Plex Mono" # Broadside preset, verbatim
  palette: ["#111111", "#1A1A18", "#E85D26", "#F0ECE5"]
assets: false
build_notes: ["one paused timeline per frame", "no remote assets", "129 BPM, dense rolls throughout — reliable beat grid", "lyric-synced: full lyrics supplied by user, mapped to real onset anchors below"]
avoid: ["generic slideshow", "literal stock-market clip-art", "unreadable tiny type", "second accent color (fire-orange is the only accent)"]
---

## Frame 1 — f1

- src: compositions/frames/01-f1.html
- duration: 16.208s
- span_sec: [0.0, 16.208]
- pacing: beat_cut
- mood: [cinematic, hype]
- feel: sparse cold-open fill explodes into a SURGE at 1s, then a dense driving groove through phrases 0-1
- lyrics: "Verse 1 (BULLS)"

### Groups

- **g1** — template: `intro-kinetic-cascade`
  - span_sec: [0.0, 8.591]
  - params: { theme: "dark", icon: "sparkle", phrases: "[\"BULLS CHARGE UP, HORNS TO THE SKY\", \"BUYING LONG, RIDING HIGH — ASKING WHY WOULD I SELL?\"]", climax: "{keyword: \"SELL?\"}" }
  - role_bindings: { phrase: { times: [1.11, 3.34, 4.88, 6.18, 7.57] }, climax: { in: 7.57, iconAt: 8.1 } }
  - copy: "BULLS CHARGE UP, HORNS TO THE SKY / BUYING LONG, RIDING HIGH — ASKING WHY WOULD I SELL?"
- **g2** — template: `intro-kinetic-cascade`
  - span_sec: [8.591, 16.208]
  - params: { theme: "dark", icon: "sparkle", phrases: "[\"THEY SEE GREEN LIKE IT'S THE ONLY COLOR GOD MADE\", \"POSITION HEAVY, LEVERAGE PAID — CONFIDENCE NEVER BETRAYED\"]", climax: "{keyword: \"BETRAYED\"}" }
  - role_bindings: { phrase: { times: [8.71, 10.4, 11.84, 13.58, 15.26] }, climax: { in: 15.26, iconAt: 16.14 } }
  - copy: "THEY SEE GREEN LIKE IT'S THE ONLY COLOR GOD MADE / POSITION HEAVY, LEVERAGE PAID — CONFIDENCE NEVER BETRAYED"

## Frame 2 — f2

- src: compositions/frames/02-f2.html
- duration: 14.953s
- span_sec: [16.208, 31.161]
- pacing: beat_cut
- mood: [cinematic, aggressive]
- feel: sustained high-energy plateau (0.78-0.88) driving hard into the track's biggest SURGE at 28s
- lyrics: "Verse 2 (BEARS)"

### Groups

- **g1** — template: `intro-kinetic-cascade`
  - span_sec: [16.208, 23.777]
  - params: { theme: "orange", icon: "sparkle", phrases: "[\"BEARS SWIPE DOWN, THEY'RE SHORTING YOUR DREAM\", \"BETTING IT BREAKS, BETTING IT BLEEDS\"]", climax: "{keyword: \"BLEEDS\"}" }
  - role_bindings: { phrase: { times: [16.9, 18.51, 19.71, 21.04, 22.41] }, climax: { in: 22.41, iconAt: 23.1 } }
  - copy: "BEARS SWIPE DOWN, THEY'RE SHORTING YOUR DREAM / BETTING IT BREAKS, BETTING IT BLEEDS"
- **g2** — template: `intro-kinetic-cascade`
  - span_sec: [23.777, 31.161]
  - params: { theme: "orange", icon: "sparkle", phrases: "[\"THEY SOLD THE SKIN 'FORE THEY CAUGHT THE BEAST\", \"EIGHTEENTH-CENTURY LONDON — THAT'S WHERE THEY WERE RELEASED\"]", climax: "{keyword: \"RELEASED\"}" }
  - role_bindings: { phrase: { times: [24.15, 25.57, 27.49, 28.77, 30.16] }, climax: { in: 30.16, iconAt: 30.81 } }
  - copy: "THEY SOLD THE SKIN 'FORE THEY CAUGHT THE BEAST / EIGHTEENTH-CENTURY LONDON — THAT'S WHERE THEY WERE RELEASED"

## Frame 3 — f3

- src: compositions/frames/03-f3.html
- duration: 18.839s
- span_sec: [31.161, 50.0]
- pacing: beat_cut
- mood: [cinematic, tense]
- feel: energy oscillates LOW/MEDIUM/HIGH across three phrases, building tension into a hard DROP at 50s
- lyrics: "Bridge, lines 1-3"

### Groups

- **g1** — template: `intro-kinetic-cascade`
  - span_sec: [31.161, 38.963]
  - params: { theme: "dark", icon: "sparkle", phrases: "[\"NOW THE SMART MONEY KNOWS:\", \"WHEN A BULL STARTS TO TIRE\"]", climax: "{keyword: \"TIRE\"}" }
  - role_bindings: { phrase: { times: [31.6, 33.02, 34.32, 35.69, 37.15] }, climax: { in: 37.15, iconAt: 37.78 } }
  - copy: "NOW THE SMART MONEY KNOWS: WHEN A BULL STARTS TO TIRE"
- **g2** — template: `intro-kinetic-cascade`
  - span_sec: [38.963, 46.579]
  - params: { theme: "orange", icon: "sparkle", phrases: "[\"A BEAR SMELLS BLOOD,\", \"AND THE SPREAD CATCHES FIRE\"]", climax: "{keyword: \"FIRE\"}" }
  - role_bindings: { phrase: { times: [39.38, 40.66, 41.91, 43.51, 44.95] }, climax: { in: 44.95, iconAt: 45.7 } }
  - copy: "A BEAR SMELLS BLOOD, AND THE SPREAD CATCHES FIRE"
- **g3** — template: `typewriter-phrase-keyword-shuffle`
  - span_sec: [46.579, 50.0]
  - params: { bgColor: "dark", textColor: "cream", accentColor: "fire-orange", lead1: "THEY BEEN FIGHTING SINCE", lead2: "THE STREET WAS JUST DIRT AND", keyword: "DESIRE", periodChar: "." }
  - role_bindings: { phrase: { times: [46.88, 47.65, 48.16, 48.85, 49.6] } }
  - copy: "THEY BEEN FIGHTING SINCE THE STREET WAS JUST DIRT AND DESIRE"

## Frame 4 — f4

- src: compositions/frames/04-f4.html
- duration: 9.0s
- span_sec: [50.0, 59.0]
- pacing: beat_cut
- mood: [cinematic, dark]
- feel: sparse, spacious passage with wide energy swings, falling to the hard stop at 59s
- lyrics: "Bridge, line 4 → Chorus, line 1"

### Groups

- **g1** — template: `intro-kinetic-cascade`
  - span_sec: [50.0, 54.219]
  - params: { theme: "dark", icon: "sparkle", phrases: "[\"TWO ANIMALS, ONE CAGE —\", \"SOMEBODY'S GETTING RETIRED.\"]", climax: "{keyword: \"RETIRED.\"}" }
  - role_bindings: { phrase: { times: [50.06, 50.83, 51.8, 52.57, 53.48] }, climax: { in: 53.48, iconAt: 54.1 } }
  - copy: "TWO ANIMALS, ONE CAGE — AND SOMEBODY'S GETTING RETIRED."
- **g2** — template: `split-anchor-word-slot`
  - span_sec: [54.219, 59.0]
  - params: { bgColor: "dark", theme: "dark", anchors: "[\"IT'S A ZOO\", \"ON THE FLOOR\"]", showText: true, program: "slot-cycle: WE SPEAK IN THE FAUNA" }
  - role_bindings: { phrase: { times: [54.5, 55.26, 56.05, 56.84, 57.82, 58.77] } }
  - copy: "IT'S A ZOO ON THE FLOOR, YEAH WE SPEAK IN THE FAUNA"

## Frame 5 — f5

- src: compositions/frames/05-f5.html
- duration: 13.0s
- span_sec: [59.0, 72.0]
- pacing: beat_cut
- mood: [cinematic, tense]
- feel: dense rebuild punctuated by two consecutive hard stops (68s, 72s) — a stutter into the final act
- lyrics: "Chorus, lines 2-3"

### Groups

- **g1** — template: `card-flyby`
  - span_sec: [59.0, 65.55]
  - params: { theme: "orange", bgColor: "orange", cards: "[\"BULLS\", \"RUN IT UP\", \"BEARS\", \"BRINGING THE TRAUMA\"]", yaw: 12 }
  - role_bindings: { landings: { times: [61.74, 62.95, 64.11, 65.39] } }
  - copy: "BULLS RUN IT UP, BEARS BRINGING THE TRAUMA"
- **g2** — template: `held-text-strobe-burst`
  - span_sec: [65.55, 68.0]
  - params: { markText: "PIGS GET SLAUGHTERED", fontStyle: "display", markScale: 1.0, idleColor: "ink-black", idleInk: "cream", duration: 2.45 }
  - role_bindings: { strobePlan: { rollStart: 65.875, rollEnd: 68.383 } }
  - copy: "PIGS GET SLAUGHTERED"
- **g3** — template: `typewriter-phrase-keyword-shuffle`
  - span_sec: [68.0, 72.0]
  - params: { bgColor: "dark", textColor: "cream", accentColor: "fire-orange", lead1: "SHEEP FOLLOW", keyword: "THE DRAMA", periodChar: "." }
  - role_bindings: { phrase: { times: [68.1, 68.71, 69.66, 70.64, 71.61] } }
  - copy: "SHEEP FOLLOW THE DRAMA"

## Frame 6 — f6

- src: compositions/frames/06-f6.html
- duration: 19.12s
- span_sec: [72.0, 91.12]
- pacing: beat_cut
- mood: [cinematic, hype]
- feel: cold VOID restart rebuilds into the heaviest bass/sub-heavy climax, sustained to the final hard stop at 91s
- lyrics: "Chorus, line 4 (hook) + closing title stamp"

### Groups

- **g1** — template: `poster-tile-mosaic`
  - span_sec: [72.0, 79.877]
  - params: { bgColor: "dark", tiles: "[\"WELCOME\", \"TO THE\", \"JUNGLE\"]", showText: true, program: "accumulate-then-recolor-on-roll" }
  - role_bindings: { anchors: { times: [73.68, 74.75, 76.02, 76.86, 77.51, 78.6] } }
  - copy: "WELCOME TO THE JUNGLE"
- **g2** — template: `intro-kinetic-cascade`
  - span_sec: [79.877, 87.0]
  - params: { theme: "orange", icon: "sparkle", phrases: "[\"WHERE THE MONEY\", \"MAKES THE KARMA\"]", climax: "{keyword: \"KARMA\"}" }
  - role_bindings: { phrase: { times: [80.2, 81.32, 82.64, 83.78, 85.36] }, climax: { in: 85.36, iconAt: 86.19 } }
  - copy: "WHERE THE MONEY MAKES THE KARMA"
- **g3** — template: `intro-kinetic-cascade`
  - span_sec: [87.0, 91.12]
  - params: { theme: "dark", icon: "sparkle", phrases: "[\"IT'S A ZOO\", \"ON THE FLOOR.\"]", climax: "{keyword: \"FLOOR.\"}" }
  - role_bindings: { phrase: { times: [87.21, 87.75, 88.47, 89.19] }, climax: { in: 89.19, iconAt: 90.0 } }
  - copy: "IT'S A ZOO ON THE FLOOR."
