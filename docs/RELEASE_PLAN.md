# JARVIS for Windows — release plan

## Phase 1: source publication

- Publish the inspected source snapshot and project documentation.
- Keep generated models, recordings, caches, secrets, and local machine configuration out of version control.
- Run automated syntax checks on every push and pull request.

## Phase 2: runtime consolidation

- Establish one supported application entry point.
- Coordinate the dashboard, voice listener, module manager, and camera lifecycle.
- Add graceful shutdown and prevent duplicate instances.
- Provide clear microphone and camera state, standby, and emergency-stop controls.

## Phase 3: gesture modes

- Preserve the existing standard mode: right-hand Air Mouse and left-hand Air Keyboard.
- Add a left-hand thumbs-up hold (three seconds) to enter Air Drawing mode.
- Keep the right-hand mouse active in drawing mode.
- Use left index-finger movement for the drawing cursor and a deliberate pinch to draw.
- Provide pen, eraser, undo, redo, clear, save, and adjustable colour/thickness controls.
- Require stable gesture recognition, reset the hold timer on tracking loss, and provide a clear mode indicator.
- Test tracking and ergonomics on real Windows webcam hardware before claiming support.

## Phase 4: Windows packaging

- Resolve subprocess and multiprocessing behaviour in frozen builds.
- Choose a packaging approach and build from a clean Windows environment.
- Test installation, first launch, permissions, camera use, microphone use, standby, stop, upgrades, and uninstall.
- Publish installer checksums and release notes. Sign binaries when code-signing is available.

## Release policy

The project may be published as a source alpha before an installer exists, but the repository must clearly identify unimplemented and untested features. Do not publish a binary as stable without clean-machine and hardware acceptance testing.
