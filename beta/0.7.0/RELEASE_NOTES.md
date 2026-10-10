# THOUGHTS 0.7.0 beta — build 27.4

This beta preserves the verified RC2 audio and visual behavior and includes the final tall-window stereo-waveform scaling correction.

Highlights:
- Stereo Diamond retains its verified Mid/Side geometry, density and persistence unchanged.
- Thoughts Lines retains chronological same-instant L/R pairs, bounded 96-point history and brief persistence.
- Catch selection, preview, export, zoom and scrolling remain unchanged.
- Settings routing, LUFS, True Peak, Analyzer, Overlay and character animations passed the focused regression suite.
- Separate stereo waveforms remain centered instead of stretching apart in unusually tall windows.

Known distribution limitation:
- This beta is ad-hoc signed because no Apple Developer ID Application certificate is installed on the build Mac.
- It is not notarized and has no stapled notarization ticket. macOS Gatekeeper may require an explicit user override.
- Apple-silicon (arm64), macOS 14 or later.

SHA-256 is provided as a separate asset. The production Sparkle appcast was not changed.
