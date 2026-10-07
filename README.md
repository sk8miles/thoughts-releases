# thoughts

Downloads and general bug reports for the thoughts Mac tester app.

- Requires macOS 14 or later.
- Source code is kept in a separate private repository.
- Tester builds are not notarized. They use ad hoc app signing and signed update archives; macOS may ask to renew system-audio access after installation.
- Updates are installed only after you choose to install and restart. Avoid installing during a performance or stream.
- No diagnostic files are uploaded automatically.

## Downloads

The app is named **thoughts**. Settings and presets from Thoughts Rolling Prototype are preserved.

Read the [user manual](MANUAL.txt).

[Download thoughts 0.6.2](https://github.com/sk8miles/thoughts-releases/releases/tag/v0.6.2) · Apple Silicon and Intel.

Use the [Releases page](https://github.com/sk8miles/thoughts-releases/releases) for published builds. A release is ready only when its ZIP and release notes are present.

A short English **Quick tour** appears once and can be skipped or reopened from the app menu, tray or Settings. It focuses on Catch selection, scrolling, Command-zoom, holding the speaker to listen and copying/dragging WAVs. Hold **Command and drag** to move in transparent mode.

## Report a bug

Use **Report a bug…** inside the app, or [open a bug report](https://github.com/sk8miles/thoughts-releases/issues/new?template=bug_report.yml).

**Issues are public.** Do not post audio, screenshots with private information, raw crash reports, personal paths, email addresses, account identifiers, or complete diagnostic files here. Exported diagnostics stay on your Mac; review them and share privately with the developer through your existing contact if needed.

The reported Ableton/OBS crash is still under investigation; its actual crash report is needed to identify the cause. Version 0.6.2 includes the Catch quick tour and local visual/trackpad polish. It preserves audio/DSP, metering, presets and the existing render cadence. Short lifecycle and sanitizer checks passed; this is not long-run leak proof or a confirmed fix for the streaming crash.
