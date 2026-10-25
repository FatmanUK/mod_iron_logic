# Sample set — Iron Logic

Status: provisional analytical selection from the actual supplied archives. Sample audition takes place after composition, as requested. The source bytes are not edited.

These are headerless raw sample files, interpreted provisionally as signed 8-bit mono PCM. There is no stored playback rate, note, finetune or loop metadata in these files. Confirm interpretation in the compiled import. All instrument finetunes are `00`; no pitch correction is silently applied.

| ID | Source | Role | Bytes (hex) | Peak | RMS quarters | DC | Rails % | Default volume |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 01 | ST-01/BassDrum2 | kick | 0BB8 | 127 | 41.20 / 29.45 / 6.64 / 2.51 | 0.98 | 0.00 | `3C` |
| 02 | ST-01/Snare2 | snare | 076C | 128 | 77.06 / 38.07 / 25.99 / 27.02 | -1.21 | 2.58 | `25` |
| 03 | ST-01/CloseHiHat | hat | 04B0 | 34 | 11.34 / 3.25 / 0.67 / 0.22 | 0.02 | 0.00 | `40` |
| 04 | ST-01/FilterBass | bass | 170C | 128 | 33.90 / 23.25 / 12.70 / 4.03 | -0.02 | 0.02 | `33` |
| 05 | ST-02/SynBuz | lead | 0E74 | 112 | 44.98 / 28.68 / 9.71 / 3.51 | -2.85 | 0.00 | `2C` |
| 06 | ST-01/KorgFilter | stab | 0D48 | 86 | 22.33 / 26.26 / 25.01 / 24.31 | -0.06 | 0.00 | `19` |
| 07 | ST-01/WoodBlock | tick | 04B0 | 119 | 33.64 / 5.12 / 1.53 / 0.37 | -0.11 | 0.00 | `26` |
| 08 | ST-02/Cymbal2 | cymbal | 0CE4 | 128 | 68.83 / 40.59 / 10.75 / 3.39 | -0.25 | 1.55 | `20` |
| 09 | ST-01/ElecTom | tom | 0BB8 | 128 | 68.68 / 48.40 / 17.98 / 6.00 | -0.26 | 0.27 | `24` |

Signal measurements use decimal sample units; a signed sample lies from -128 to +127. RMS quarters are chronological, equal-duration portions of the unchanged file. Rail percentage counts samples exactly at -128 or +127; it is evidence of saturation risk, not proof of audible clipping. Volumes and IDs are hexadecimal.

- `01` ST-01/BassDrum2: Rounded low strike rather than a saturated archive kick.
- `02` ST-01/Snare2: Rough, persistent noise tail suits the heavy half-time role; check the ending click.
- `03` ST-01/CloseHiHat: Quiet source kept at full default so the low rhythm remains dominant.
- `04` ST-01/FilterBass: Harmonic low body gives the press weight; it already decays naturally.
- `05` ST-02/SynBuz: Raised by an octave relative to bass labels for an audible command signal.
- `06` ST-01/KorgFilter: Low finite pressure indicator.
- `07` ST-01/WoodBlock: Brief dry marker with a very low late tail.
- `08` ST-02/Cymbal2: Punctuation at the broad transfer and final stroke.
- `09` ST-01/ElecTom: Single-pitch roll becomes the final release mechanism.

## Suitability, register and balance

Every pitched part is a single monophonic line; there are no chord samples or arpeggiator effects. Pitched sample spectra are broadly consistent with C-related harmonic material; this is provisional suitability evidence, not a by-ear confirmation that every source is an ideal single note. Inharmonic bells and attack noise should not be mistaken for deliberately layered chords.

Default volumes balance source RMS, peak and role. Percussion with large peaks is attenuated; the quiet CloseHiHat, when selected, uses its full source level. Per-row accents remain explicit in the tables. A lower default cannot undo clipping already present in source audio.

DXBass was excluded because its source has a very large DC offset. CowBell was excluded from these sets because of substantial rail occupancy and DC. Where a saturated kick/snare is selected, its grit is a deliberate provisional timbral choice and is identified above. No reverse or ping-pong behaviour is used.

All selected envelopes are used as finite events. No sustained pad role is required; see `loops.md` for loopability decisions and the KorgFilter seam diagnostic. The exact written pitch subsets and provisional source-root estimates are in `ranges.md`.

## Sample audition criteria — after composition

- Solo each instrument at every actual trigger pitch in `ranges.md`, using its metadata volume first. Confirm signed PCM interpretation, note identity, register, attack quality and tail behaviour.
- Compare bass and main voice on the same named tonic and fifth; allow their planned octave separation, then listen for unintended detuning or beating. Keep finetune zero unless the brief is explicitly changed.
- Check the pitched samples are perceived as single notes. If a source sounds like a fixed chord, report that source and exact trigger; do not approve it merely because the spectrum looked harmonic.
- Check low sample endings and every gate for clicks. Evaluate noisy percussion tails at both normal and quiet monitoring levels. Check deliberately saturated sources for useful grit versus objectionable harshness.
- Check kick/bass balance, main-voice intelligibility and hat/tick audibility in the complete ensemble and in mono. Compare the initial group with the densest group before deciding defaults.
- Preserve accepted by-ear sample volumes, loop changes, finetune and row edits in the actual auditioned project. Return that exact project with notes so the source can be reconciled.

Piece-specific check: The single snare on row 08 of each sixteen-row bar must feel deliberately heavy. Check that the longer snare tail does not sound like a loop or swamp the wood marker.
