# Orlon Voice

Fast, lightweight voice dictation that turns speech into clean text anywhere on your computer.

Orlon Voice runs quietly in the background. Press your shortcut, speak naturally, and your words are transcribed and inserted where you were typing.

## Features

- System-wide voice dictation
- Customizable keyboard shortcut
- Small floating voice indicator while recording
- Automatic transcription after speaking
- Inserts text directly into the active application
- Local-first architecture
- Temporary audio is deleted after transcription
- Lightweight background operation
- Minimal desktop interface

## How it works

1. Open Orlon Voice.
2. Enable voice dictation.
3. Set your preferred shortcut.
4. Close the settings window.
5. Press your shortcut anywhere on your computer.
6. Speak.
7. Press the shortcut again to finish.
8. Orlon Voice transcribes your speech and inserts the text at your cursor.

The goal is simple:

**Shortcut → Speak → Text appears.**

## Installation

Orlon Voice is currently being developed primarily for Linux.

### AppImage

Download the latest AppImage from the Releases page.

Make it executable:

```bash
chmod +x OrlonVoice-x86_64.AppImage
```

Run it:

```bash
./OrlonVoice-x86_64.AppImage
```

No traditional installation is required.

## Linux support

Development currently focuses on:

- Fedora
- GNOME
- Wayland

Support for additional Linux distributions and desktop environments is planned.

## Privacy

Orlon Voice is designed with privacy in mind.

By default:

- recording only begins when you activate the shortcut
- microphone audio is used only for transcription
- temporary recordings are deleted after transcription
- no unnecessary user data is collected
- local transcription can be used without sending audio to a cloud service

Cloud transcription may be offered as an optional feature in the future.

## Design

Orlon Voice is intentionally small.

There are no dashboards, feeds, statistics pages, or unnecessary controls.

The main application only handles:

- enabling Orlon Voice
- configuring your shortcut

Everything else happens quietly in the background.

## Roadmap

Planned features include:

- push-to-talk mode
- improved live waveform
- faster local transcription
- automatic punctuation and cleanup
- custom vocabulary
- app-aware formatting
- selected-text voice editing
- additional transcription providers
- Windows support
- broader Linux desktop support

## Building from source

Build instructions will be added as the project stabilizes.

The project is being designed so releases can be packaged as a standard Linux AppImage.

## Contributing

Issues, bug reports, ideas, and pull requests are welcome.

If you find a problem, please include:

- Linux distribution
- desktop environment
- Wayland or X11
- Orlon Voice version
- steps to reproduce the issue

## Project status

Orlon Voice is currently in early development.

Expect changes while the dictation experience, Linux integration, and transcription pipeline are refined.

---

Built by **Orlon Technologies**.
