# Speed and tempo — Iron Logic

| Setting | Value |
| --- | --- |
| Initial speed | `06` ticks per row |
| Initial BPM | `80` hex = 128 decimal |
| Full pattern duration | 7.500000 seconds |
| Order positions | `20` |
| Nominal full-order duration | 240.000 seconds |

A slow, heavy stamping mechanism: a half-time snare, broad low FilterBass strikes and short buzzer signals above it.

The tempo is a new composition decision for this piece. CIA-style timing is assumed for the calculation: row duration = speed × 2.5 / BPM. Initial Fxx commands match `song.yaml`. There are no later tempo changes, row delays or pattern breaks. F00 on the last row can shorten the final row according to replay handling; measured duration remains pending.

The six-tick grid allows both sustained body and short tick-four gates without relying on XM envelopes.
