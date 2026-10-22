# Playback Verification

## 2026-10-22

- Operating surface: static index.html; no build or test runner is configured.
- Focused proof: Node VM syntax checks and mocked audio/Drive checks cover source-preserving advancement, cached playback without a token, pause state, and preload-completion continuation.
- Friction: the terminal initially opened outside the workspace; use the workspace directory explicitly.
- Proof ceiling: simulated media events cannot prove iOS/Android background execution, screen-lock transitions, or Google authorization on a real device.
- Magic wand: a repeatable playback regression command plus a real-device screen-lock checklist.
- Inferred rather than proved: preserving the media element's playback session will improve mobile background transitions; verify across multiple real tracks with the screen locked.