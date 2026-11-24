# Privacy and device access

This is a development snapshot, not a completed privacy-audited product.

- The voice runtime accesses the selected microphone while it is running and uses a local Vosk model for speech recognition.
- The webcam is activated by the hand-control runtime when the hand modules start; the camera manager owns the webcam in a separate process.
- The source snapshot does not implement telemetry or a cloud AI service.
- Windows speech output uses the locally installed System.Speech voice through PowerShell.
- A finished application should show clear microphone/camera status and provide an obvious stop control.

Review third-party library and model licences and privacy terms before redistribution.
