# Neighbourhood 311

## Live Mandarin recording

1. Unzip the full project folder and open Terminal in that folder.
2. Run `python3 run_311.py` using Python 3.8 or newer.
3. Enter your ElevenLabs API key at the hidden prompt. The app opens at `http://127.0.0.1:8311/`. Keep the Terminal window open.
4. Choose **Start recording**, allow microphone access and describe a streetlight issue in Mandarin. Choose **Stop recording**, then **Transcribe and translate**.
5. The recording is sent to ElevenLabs Scribe v2. Review the English issue, address and description, and expand **View original Mandarin transcript** to compare. Fill in missing fields or correct them before choosing **Confirm and preview**.
6. Choose **Simulate submission**, or try **Request an interpreter** from the review screen. Both are prototype interactions.

The key stays in the local launcher. Live mode needs internet access and ElevenLabs credits. Use a fictional address for the demo. If the provider returns a transcript without a usable English draft, the app keeps the original transcript and lets you fill in the report manually.

## Offline demo

Open `311-prototype.html` in Safari or Chrome. Choose **Use sample and continue** to walk through the simulated address error. Change **12 Maple Street** to **120 Maple Street** and preview the corrected report.

## Research and submission

Open `Voice Access Lab.html` for the ward coverage chart and FLEURS recordings. The `voice-audit` folder includes the batch transcription runner, audio credits and methods.

See `Devpost Project and Demo.md` for project copy, the two-minute demo script and upload instructions.

[ElevenLabs Scribe documentation](https://elevenlabs.io/docs/api-reference/speech-to-text/convert)
