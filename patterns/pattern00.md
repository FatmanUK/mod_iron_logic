# Pattern 00 — Working rule

Group A; harmonic bars: Cm, Cm, Cm, Cm. Logical length: 64 rows. Status: complete source draft, not auditioned.

First half uses a; second half uses b.

Ch1 kick and half-time snare; Ch2 FilterBass; Ch3 raised SynBuz command signals; Ch4 pressure stabs, quiet hats, WoodBlock and tom fills.

## Effects used here

Cxx sets channel volume immediately, from `00` silence to `40` maximum. Each written note includes its instrument; its default volume is restored at the next trigger before any row effect.
EC4 cuts that channel at tick 04 within the row; the next written trigger restores the sample default. There are no inherited slides or vibrato settings.
F06 sets ticks per row; F80 sets BPM to 128 decimal. They are on separate channels of the first row and agree with metadata.

| Row | Ch1 | Ch2 | Ch3 | Ch4 |
| --- | --- | --- | --- | --- |
| 00 | C-4 01 F06 | C-4 04 --- | C-5 05 C2C | C-4 08 F80 |
| 04 | --- -- --- | --- -- --- | --- -- --- | C-4 03 C38 |
| 05 | C-4 01 C36 | G-4 04 --- | --- -- --- | --- -- --- |
| 06 | --- -- --- | --- -- --- | G-5 05 C28 | C-4 03 C40 |
| 08 | C-4 02 C25 | --- -- --- | --- -- --- | --- -- --- |
| 10 | C-4 01 C36 | C-4 04 EC4 | --- -- --- | C-4 03 C40 |
| 12 | --- -- --- | --- -- --- | D#5 05 C2C | C-4 03 C38 |
| 14 | C-4 01 C36 | D#4 04 --- | --- -- --- | C-4 03 C40 |
| 15 | --- -- --- | --- -- --- | --- -- --- | C-4 07 C26 |
| 16 | C-4 01 C3C | C-4 04 --- | --- -- --- | --- -- --- |
| 18 | --- -- --- | --- -- --- | --- -- --- | C-4 03 C40 |
| 20 | --- -- --- | --- -- --- | --- -- --- | C-4 03 C38 |
| 22 | C-4 01 C36 | G-4 04 --- | D-5 05 C28 | C-4 03 C40 |
| 24 | C-4 02 C25 | --- -- --- | --- -- --- | --- -- --- |
| 26 | --- -- --- | C-4 04 EC4 | --- -- --- | C-4 03 C40 |
| 27 | C-4 01 C36 | --- -- --- | --- -- --- | --- -- --- |
| 28 | --- -- --- | --- -- --- | C-5 05 C2C | C-4 03 C38 |
| 29 | --- -- --- | D#4 04 --- | --- -- --- | --- -- --- |
| 30 | --- -- --- | --- -- --- | --- -- --- | C-4 03 C40 |
| 31 | --- -- --- | --- -- --- | --- -- --- | C-4 07 C26 |
| 32 | C-4 01 C3C | C-4 04 --- | --- -- --- | C-3 06 C19 |
| 34 | --- -- --- | --- -- --- | G-5 05 C2C | --- -- --- |
| 36 | --- -- --- | --- -- --- | --- -- --- | C-4 03 C38 |
| 37 | C-4 01 C36 | G-4 04 --- | --- -- --- | --- -- --- |
| 38 | --- -- --- | --- -- --- | --- -- --- | C-4 03 C40 |
| 40 | C-4 02 C25 | --- -- --- | --- -- --- | --- -- --- |
| 42 | C-4 01 C36 | C-4 04 EC4 | D#5 05 C28 | C-4 03 C40 |
| 44 | --- -- --- | --- -- --- | --- -- --- | C-4 03 C38 |
| 46 | C-4 01 C36 | D#4 04 --- | --- -- --- | C-4 03 C40 |
| 47 | --- -- --- | --- -- --- | --- -- --- | C-4 07 C26 |
| 48 | C-4 01 C3C | C-4 04 --- | --- -- --- | --- -- --- |
| 50 | --- -- --- | --- -- --- | C-5 05 C2C | C-4 03 C40 |
| 52 | --- -- --- | --- -- --- | --- -- --- | C-4 03 C38 |
| 54 | C-4 01 C36 | G-4 04 --- | --- -- --- | C-4 03 C40 |
| 56 | C-4 02 C25 | --- -- --- | --- -- --- | --- -- --- |
| 58 | --- -- --- | C-4 04 EC4 | A#4 05 C28 | C-4 03 C40 |
| 59 | C-4 01 C36 | --- -- --- | --- -- --- | --- -- --- |
| 60 | --- -- --- | --- -- --- | --- -- --- | C-4 03 C38 |
| 61 | --- -- --- | D#4 04 --- | --- -- --- | --- -- --- |
| 62 | --- -- --- | --- -- --- | --- -- --- | C-4 03 C40 |
| 63 | --- -- --- | --- -- --- | --- -- --- | C-4 07 C26 |

## Audition criteria

- Listen to this entire pattern inside its complete group, then at every order-list occurrence. Check the melodic breath between the two halves, the bass response and the deliberate percussion handoffs.
- Check each EC cut and each percussion replacement of a pitched voice for a musically acceptable edge. Notes are single-voice events; tails can be deliberately interrupted on the same channel.
- Check balance in normal stereo and mono. The bass must remain a coherent line beneath the melodic signal, and short hats/ticks must remain audible without taking over.
- The single snare on row 08 of each sixteen-row bar must feel deliberately heavy. Check that the longer snare tail does not sound like a loop or swamp the wood marker.
- The ensemble identity should already be present at the beginning. Confirm initial speed/BPM after compilation; a later reuse of this group must feel like a return, not an intro restarting.
