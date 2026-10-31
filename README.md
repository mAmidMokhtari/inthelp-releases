<div align="center">

<img src="https://raw.githubusercontent.com/mAmidMokhtari/meeting-copilot-releases/main/icon.png" width="96" alt="">

# Meeting Copilot

**Live captions and instant reply suggestions for your calls, running privately on your own computer.**

[**Download the latest version**](https://github.com/mAmidMokhtari/meeting-copilot-releases/releases/latest)

Windows · Linux · macOS (Apple Silicon)

</div>

---

## What it does

Meeting Copilot listens to your call (Zoom, Google Meet, Microsoft Teams, Skype, or anything else that plays through your speakers) and helps you answer well.

- **Live captions.** What the other side says appears on screen as they speak. Persian, English and about 100 other languages are supported.
- **Reply suggestions.** When a question is asked, Meeting Copilot suggests an answer based on your own notes and documents: your CV, product sheets, FAQs or meeting notes.
- **Your references.** Add PDF, Word, text or Markdown files. Only the passages that matter for each question are used, so a large library stays fast.
- **Private by design.** Speech recognition and suggestions run on your computer. Your audio and your documents are never uploaded.
- **Stays out of the way.** A compact window that stays on top of your call, with adjustable transparency.
- **Automatic updates.** New versions install with one click from inside the app.

## Download

Open the [latest release](https://github.com/mAmidMokhtari/meeting-copilot-releases/releases/latest) and download the file for your computer:

| Your computer | File |
| --- | --- |
| Windows 10 or 11 (64-bit) | `MeetingCopilot-Setup-<version>.exe` |
| Linux (x86-64) | `MeetingCopilot-<version>-x86_64.AppImage` |
| Mac with Apple Silicon (M1 or newer) | `MeetingCopilot-<version>-arm64.dmg` |

## Installation

### Windows

1. Run `MeetingCopilot-Setup-<version>.exe`. No administrator rights are needed.
2. If Windows shows a blue SmartScreen message, click **More info**, then **Run anyway**.
3. Start Meeting Copilot from the Start menu.

### Linux

1. Make the file executable: `chmod +x MeetingCopilot-*.AppImage`, or tick **Allow executing file as program** in its Properties.
2. Double-click it to start. Nothing else needs to be installed.

System audio is captured from PulseAudio or PipeWire. Ubuntu 22.04 or newer (or a distribution of the same age) is required.

### macOS

1. Open the `.dmg` file and drag the app into **Applications**.
2. The first time, right-click the app and choose **Open**. On macOS 15 and later, go to **System Settings › Privacy & Security** and click **Open Anyway**.
3. Allow microphone access when asked.

**To capture the other side of a call on a Mac**, which has no built-in way to record system audio:

1. Install the free [BlackHole 2ch](https://existential.audio/blackhole/) audio driver.
2. Open **Audio MIDI Setup**, click **+** and create a **Multi-Output Device** that includes both your speakers or headphones and **BlackHole 2ch**.
3. Select that Multi-Output Device as your sound output. Meeting Copilot finds BlackHole automatically.

## Getting started

1. **Activate.** Enter your license key, or start the free 3-day trial.
2. **Add your references.** Click **References** and add your notes and files.
3. **Choose the audio source.**
   - **System audio (them):** the other side of the call.
   - **Microphone:** your own voice or the room.
   - **Both:** both sides, labelled separately. Use headphones so the audio is not recorded twice.
4. **Press Start.**

On first use, Meeting Copilot downloads the components it needs, such as the speech engine and the suggestion model you pick. Progress is shown in the **Downloads** window. Reply suggestions also need the free AI engine app; Meeting Copilot shows a **Download engine** button when it is missing.

### Suggestion quality

Pick the level that suits your computer from the menu above the suggestions:

| Level | Best for |
| --- | --- |
| **Fast** | The quickest answers, and lighter on older computers |
| **Standard** | A good balance of speed and quality (recommended) |
| **Accurate** | The best answers; needs a strong graphics card |

## System requirements

| | Minimum | Recommended |
| --- | --- | --- |
| Memory | 8 GB RAM | 16 GB RAM |
| Disk space | 6 GB free | 10 GB free |
| Graphics | Not required | NVIDIA card with 6 GB or more (Windows); Apple Silicon (Mac) |
| Internet | For activation, first-time downloads and updates | |

Without a supported graphics card, everything runs on the processor. It still works, just more slowly.

## Subscription and support

Meeting Copilot needs an active subscription after the trial. To buy or renew, or for help, use **Contact support** in the app (also in the **Account** window).

When reporting a problem, please include the app version from the **Account** window.

## Privacy

- Audio is processed on your computer and is never recorded to disk or uploaded.
- Your notes and reference files stay on your computer.
- The app only contacts the license server to check your subscription and to look for updates.

---

<div align="center"><sub>This repository hosts release downloads only.</sub></div>
