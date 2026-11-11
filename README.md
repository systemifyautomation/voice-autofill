# Voice Auto-fill

Speak into a text field and Voice Auto-fill writes for you. Activate the field you want, record your voice, and the transcription is inserted directly where you are typing.

## Setup

1. Open `chrome://extensions` in Chrome.
2. Enable Developer mode and select **Load unpacked**.
3. Choose this repository's `chrome-extension` folder.
4. Open Voice Auto-fill from the Chrome toolbar and save your OpenAI API key.

## Use

1. Focus the text field you want to fill.
2. Choose **Enable on focused field** in the extension popup, or press `Alt+Shift+V`.
3. Select the microphone button, speak, then select it again to stop.

The controls appear only on fields you enable. Use the ON/OFF control in the popup to hide all in-page controls at any time.

## Notes

Your API key is stored locally in Chrome. Audio is sent to OpenAI for transcription.
