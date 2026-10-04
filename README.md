# Talktomyhand

Voice dictation for Mac. Hold **fn**, speak, and clean, formatted text appears at your cursor in any app.

**[Download the latest version](https://github.com/pranavsaji/talktomyhand-releases/releases/latest)**

Requires an Apple Silicon Mac on macOS 14 or later.

## Install

1. Download the latest `.dmg` from [Releases](https://github.com/pranavsaji/talktomyhand-releases/releases/latest) and open it.
2. Drag **Talktomyhand** onto the Applications folder, then open it from Applications. The app is signed and notarized by Apple, so it opens like any other app.
3. Follow the setup window: allow Microphone and Accessibility, and set the 🌐 fn key to "Do Nothing" in Keyboard settings.
4. Create a free account on the **Account** page (2,000 words a week, no API key needed), or paste your own [Groq API key](https://console.groq.com/keys) in Settings for unlimited use.

Updating from 1.1.0 or earlier: macOS will ask you to allow Microphone and Accessibility once more, because the app is now signed with an Apple Developer ID.

## What it does

- Hold fn to dictate; double-tap fn for hands-free
- AI cleanup: removes fillers, applies self-corrections, fixes punctuation, formats lists, numbers and emails
- Personal dictionary and searchable history
- On-device mode, where nothing leaves your Mac
- Pro: Command Mode (edit selected text by voice), Polish, snippets, voice notes, per-app writing styles, translation

## How your audio is handled

You choose the mode in Settings:

| Mode | Where audio and text go |
| --- | --- |
| Talktomyhand Cloud (signed in) | Through our server to Groq for transcription, then back. Not stored by us; we keep only word counts. |
| Your own Groq key | Straight from your Mac to Groq. We receive nothing. |
| On-device | Stays on your Mac. |

History, dictionary, notes and saved audio are stored only on your Mac.
