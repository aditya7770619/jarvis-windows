# Contributing to JARVIS for Windows

Thanks for your interest. JARVIS is experimental software that can control mouse and keyboard input and access microphone and webcam devices.

## Before contributing
- Read `README.md` and `docs/PRIVACY.md`.
- Do not submit API keys, credentials, personal recordings, camera captures, microphone recordings, model binaries, or machine-specific configuration.
- Keep changes focused and explain how they were tested.
- Do not claim hardware behaviour is tested unless it was tested on real Windows hardware.

## Development checks
Install `requirements-windows.txt`, then run:

```powershell
python -m compileall -q .
```

Hardware tests should record Windows version, Python version, camera model, microphone selection, and the exact interaction tested. Remove personal data and secrets from logs before posting.

## Pull requests
Include a concise problem statement, scope, test evidence, known limitations, and screenshots only when they do not expose private information.
