# Tanpura Waveguide Synthesizer

A physics-based tanpura simulator that runs entirely in the browser.

**Open the app:** https://nraravikar-source.github.io/tanpura/

The sound is computed (not sampled) from a digital-waveguide model of four stiff strings with:

- a one-sided contact barrier for the jawari bridge and thread,
- frequency-dependent string losses,
- all-pass dispersion filters for string stiffness (inharmonicity),
- a modal resonator bank for the gourd / body.

Adjustable parameters include pitch (Sa), string material, diameter and tension, bridge profile, thread position and thickness, pluck, damping and body type. Output is audio (playback and WAV download) with an averaged spectrum, a spectrogram and a harmonic-level table, plus a saved reference for A/B comparisons.

Everything is in a single file, `index.html`. No installation or server is needed, and no data is collected.

Body resonance values are illustrative, not measurements of a particular instrument.
