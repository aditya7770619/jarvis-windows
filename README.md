# JARVIS for Windows

**A personal voice- and gesture-controlled desktop assistant.**

> **Status: early public alpha — source preview, not a ready-to-install application.**

JARVIS is an experimental Windows desktop project exploring hands-free computer interaction through voice commands, webcam-based hand tracking, an air mouse, a virtual keyboard, and air drawing.

## Current project direction

- Voice wake word and voice-controlled module activation
- Webcam hand tracking
- Air mouse and air keyboard
- Gesture-controlled drawing and writing (under development)
- A central module and camera management architecture
- Future workspace automation and visual assistance

Features are at different stages of development. Please consult the release notes and issue tracker before relying on any feature.

## Important notice

This repository is an early development snapshot. It is **not yet a supported installer or a verified public release**. No signed Windows installer is provided at this stage. Hardware support, webcam behaviour, microphone compatibility, and clean-machine installation have not yet been validated across devices.

Do not install or run code you do not understand. Review scripts before execution. Do not commit API keys, passwords, personal documents, recordings, or other secrets.

## Development environment

The original development environment used Windows and Python 3.14. Exact dependency compatibility and packaging are still being validated. No guarantee is made that the project runs unchanged on another machine.

## Planned milestones

1. Consolidate voice, camera, module, and desktop application startup.
2. Integrate and validate air drawing/writing mode.
3. Improve gesture reliability, accessibility, and ergonomic controls.
4. Add repeatable Windows packaging and clean-install tests.
5. Publish a tested alpha installer with checksums and release notes.

## Privacy

JARVIS uses microphone and webcam input for local interaction features. Before public distribution, the project will document exactly what is captured, where it is processed, and whether anything is transmitted. Until that review is complete, treat this as experimental software and avoid using it in sensitive environments.

## Contributing

Issues and suggestions are welcome. Please include Windows version, Python version, hardware details, reproduction steps, and relevant logs. Remove personal data and secrets from logs before posting.

## License

MIT License. See [LICENSE](LICENSE).

---

Built as an experimental personal computing project. Contributions and careful testing are welcome.
