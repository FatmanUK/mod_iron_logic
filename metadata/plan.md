# Pattern plan — Iron Logic

Group membership is exclusive; each group contains at most four patterns. Patterns were written sequentially, group by group, beginning with pattern00.

| Group | Pattern members | Role |
| --- | --- | --- |
| A | 00 01 02 03 | First complete working state |
| B | 04 05 06 07 | Alternate working / pressure state |
| C | 08 09 0a 0b | One-time terminal route and coda |

Group order: **A B A B B A B C**.

A is a four-pattern C-minor working cycle, including one B-flat diversion. B moves through A-flat and B-flat, then returns to C without reducing the ensemble. Repeated A and B cycles build inevitability through context. C is a one-time four-pattern release route, ending in a tom-led final press stroke.

| Pattern | Harmonic bars | Fragments | Purpose |
| --- | --- | --- | --- |
| 00 | Cm, Cm, Cm, Cm | a / b | Working rule |
| 01 | Cm, Cm, Cm, Cm | f / a | Repeated command |
| 02 | A#, A#, A#, A# | c / b | Pressure redirected |
| 03 | Cm, Cm, Cm, Cm | e / a | Ram seats |
| 04 | G#, G#, G#, G# | d / g | Load transferred |
| 05 | A#, A#, A#, A# | c / h | Return path |
| 06 | Cm, Cm, Cm, Cm | f / e | Double command |
| 07 | Cm, Cm, Cm, Cm | a / f | Load held |
| 08 | Fm, Fm, G#, G# | g / d | Release channel |
| 09 | A#, A#, A#, A# | c / h | Counterforce |
| 0a | Cm, Cm, Cm, Cm | e / f | Final instruction |
| 0b | Cm, Cm, Cm, Cm | a / independent coda | Last press stroke |

| Order position (hex) | Pattern |
| --- | --- |
| 00 | 00 |
| 01 | 01 |
| 02 | 02 |
| 03 | 03 |
| 04 | 04 |
| 05 | 05 |
| 06 | 06 |
| 07 | 07 |
| 08 | 00 |
| 09 | 01 |
| 0A | 02 |
| 0B | 03 |
| 0C | 04 |
| 0D | 05 |
| 0E | 06 |
| 0F | 07 |
| 10 | 04 |
| 11 | 05 |
| 12 | 06 |
| 13 | 07 |
| 14 | 00 |
| 15 | 01 |
| 16 | 02 |
| 17 | 03 |
| 18 | 04 |
| 19 | 05 |
| 1A | 06 |
| 1B | 07 |
| 1C | 08 |
| 1D | 09 |
| 1E | 0a |
| 1F | 0b |

Nominal duration is 240.000 seconds before terminal-row stop nuances. Standard MOD size estimate is 39,972 bytes, including 26,600 raw sample bytes and twelve pattern blocks. These are calculations, not compiled measurements.

All patterns have 64 logical rows. Omitted table rows are entirely empty rows; the compiler must expand them. There are no Dxx breaks, Bxx order jumps, E6x musical loops or tempo changes. Order-list reuse, rather than flow-control effects, creates the structure. The last pattern contains an articulated final flourish and F00. Player stop handling is pending validation.
