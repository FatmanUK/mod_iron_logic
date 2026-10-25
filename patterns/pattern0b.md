# Pattern 0b — Last press stroke

Group C; harmonic bars: Cm, Cm, Cm, Cm. Logical length: 64 rows. Status: complete source draft, not auditioned.

First half recalls a; the second half is the independently written last compression coda.

Ch1 kick and half-time snare; Ch2 FilterBass; Ch3 raised SynBuz command signals; Ch4 pressure stabs, quiet hats, WoodBlock and tom fills.

## Effects used here

Cxx sets channel volume immediately, from `00` silence to `40` maximum. Each written note includes its instrument; its default volume is restored at the next trigger before any row effect.
EC4 cuts that channel at tick 04 within the row; the next written trigger restores the sample default. There are no inherited slides or vibrato settings.
F00 requests playback stop on row 63. The final hit is followed by a fixed silence boundary, not a volume fade. Stop handling remains a required check in the compiled MOD and the user’s MilkyTracker replay mode.

| Row | Ch1 | Ch2 | Ch3 | Ch4 |
| --- | --- | --- | --- | --- |
| 00 | C-4 01 C3C | C-4 04 --- | C-5 05 C2C | C-3 06 C19 |
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
| 32 | C-4 01 C3C | C-4 04 --- | G-5 05 C2C | --- -- --- |
| 36 | --- -- --- | --- -- --- | --- -- --- | C-4 09 C18 |
| 40 | C-4 02 C25 | G-4 04 EC4 | D#5 05 C2C | --- -- --- |
| 42 | --- -- --- | --- -- --- | --- -- --- | C-4 09 C1C |
| 44 | --- -- --- | --- -- --- | --- -- --- | C-4 09 C20 |
| 46 | C-4 02 C25 | D#4 04 EC4 | D-5 05 C28 | --- -- --- |
| 47 | --- -- --- | --- -- --- | --- -- --- | C-4 09 C24 |
| 49 | --- -- --- | --- -- --- | --- -- --- | C-4 09 C28 |
| 50 | C-4 02 C25 | G-4 04 EC4 | C-5 05 C2C | --- -- --- |
| 51 | --- -- --- | --- -- --- | --- -- --- | C-4 09 C2C |
| 54 | C-4 01 C3C | C-4 04 --- | C-5 05 C2C | C-4 08 C20 |
| 60 | --- -- C00 | --- -- C00 | --- -- C00 | --- -- C00 |
| 63 | --- -- F00 | --- -- --- | --- -- --- | --- -- --- |

## Audition criteria

- Listen to this entire pattern inside its complete group, then at every order-list occurrence. Check the melodic breath between the two halves, the bass response and the deliberate percussion handoffs.
- Check each EC cut and each percussion replacement of a pitched voice for a musically acceptable edge. Notes are single-voice events; tails can be deliberately interrupted on the same channel.
- Check balance in normal stereo and mono. The bass must remain a coherent line beneath the melodic signal, and short hats/ticks must remain audible without taking over.
- The single snare on row 08 of each sixteen-row bar must feel deliberately heavy. Check that the longer snare tail does not sound like a loop or swamp the wood marker.
- Check the last full group flows into the distinct flourish, the root landing is convincing, and the final cut does not steal a needed tail. Verify F00 stops, all channels are silent, and pattern00 does not restart.
