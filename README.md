# JARVIS for Windows

**A personal voice- and gesture-controlled desktop assistant.**

> **Status: early public alpha — project scaffold and documentation are published; the source bundle is being added. This is not a ready-to-install application.**

JARVIS is an experimental Windows desktop project exploring hands-free computer interaction through voice commands, webcam-based hand tracking, an air mouse, a virtual keyboard, and air drawing.

## Repository status

The public repository currently contains the project overview, licence, contribution/security guidance, privacy notes, release plan, checklist, and a source-check workflow. **The full Python source bundle is not yet committed to this repository.** Do not treat this repository as a complete downloadable build until the source bundle is uploaded and reviewed.

## Current project direction

- Voice wake word and voice-controlled module activation
- Webcam hand tracking
- Air mouse and air keyboard
- Gesture-controlled drawing and writing (under development)
- A central module and camera management architecture
- Future workspace automation and visual assistance

Features are at different stages of development. Please consult docs/BUILD_STATUS.md and the release checklist before relying on any feature.

## Important notice

This repository is an early development snapshot. It is **not yet a supported installer or a verified public release**. No signed Windows installer is provided at this stage. Hardware support, webcam behaviour, microphone compatibility, and clean-machine installation have not yet been validated across devices.

Do not install or run code you do not understand. Review scripts before execution. Do not commit API keys, passwords, personal documents, recordings, or other secrets.

## Planned milestones

1. Complete source publication and review.
2. Consolidate dashboard, voice, camera, and module startup.
3. Integrate and validate air drawing/writing mode.
4. Add repeatable Windows packaging and clean-install tests.
5. Publish a tested alpha installer with checksums and release notes.

## Privacy

JARVIS uses microphone and webcam input for local interaction features. Review docs/PRIVACY.md. The privacy description is preliminary and must be validated against the final code before wider distribution.

## Contributing

Issues and suggestions are welcome. Please include Windows version, Python version, hardware details, reproduction steps, and relevant logs. Remove personal data and secrets from logs before posting.

## License

MIT License. See LICENSE.

---

Built as an experimental personal computing project. Contributions and careful testing are welcome.
