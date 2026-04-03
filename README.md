# PushToTalkSTT

A Windows speech-to-text app in a single `.exe` file.

1. Open the app
2. Hold **Ctrl + Windows key** to record.
3. Release the keys to stop.
4. The app transcribes your speech, copies the text, and pastes it where your cursor is active.

## Included in this release

This release contains only:

- `PushToTalkSTT.exe`

No setup steps are required beyond running the executable.

## Features

- Push-to-talk recording
- Speech-to-text
- Automatic copy to clipboard
- Automatic paste at the current cursor position
- Packaged as a single Windows executable

## Requirements

- Windows 10 or 11
- A working microphone
- Permission for microphone access in Windows

## Notes

- First startup may take longer than normal
- Windows SmartScreen or antivirus may scan the `.exe` on first launch
- The app uses simulated paste, so some programs may block it
- The **Windows key** hotkey may conflict with some system shortcuts on some PCs

## Troubleshooting

### Nothing happens when I press the hotkey

- Make sure the app is running
- Check that your microphone is connected and working
- Try running the app as Administrator
- Some systems may conflict with **Ctrl + Windows key**

### It records but does not paste

- Click into a normal text box first
- Test in Notepad
- Some apps block simulated keyboard paste actions

### Microphone does not work

- Enable microphone permission in Windows Privacy settings
- Test the microphone in Windows Sound settings
- Make sure the correct input device is selected

### Windows says the file is untrusted

That can happen with newly built unsigned `.exe` files. You may need to allow it manually.

## Usage tip

For better results:

- hold the hotkey first
- speak clearly
- release the hotkey after finishing your sentence
