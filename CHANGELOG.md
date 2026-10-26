# Changelog

Each release is tagged `vX.Y.Z` on GitHub; its notes are copied from here.

## 1.1.0

- **Glows fade if you don't look.** A glow nobody hovers now fades after 10 minutes, and its message waits in the notch until you do. Running tasks and questions keep glowing. Change the time, or turn it off, in Settings → General → Notifications.
- **Focus and Do Not Disturb.** In System Settings → Focus → (a Focus) → Focus Filters, add Blotch and pick *Quiet* (no pop-ups or sounds) or *Still* (no glow or sneak peek either). Questions from coding agents still pop open.
- **Lighter on battery.** The glow pulse and the music bars draw at most 30 frames a second, and the glow is no longer redrawn from scratch while your screen is recorded or shared.

## 1.0.0

First public release.

- **Status glow** around the notch: Running, Done, Needs you, Failed, in colors you pick.
- **`blotch` CLI, socket and `blotch://` URLs**, so scripts, terminals, CI and Shortcuts can show activities, progress and questions in the notch. `blotch run`, `blotch ask`, `blotch timer`, and a zsh hook for slow commands.
- **Coding agents:** Claude Code and Codex light up the notch while they work, when they need you and when they finish. Approve Claude Code's permission requests from the notch.
- **Drop actions:** OCR, remove background, compress, GIF, merge PDFs, zip, AirDrop and Convert to… for images, video, audio and documents. On-device AI text actions on macOS 26.
- **Screenshots and screen recording** from the notch, with follow-up actions.
- **Widgets:** Now Playing with music bars, finished downloads, calendar with Join buttons, connection and battery alerts, clipboard tools, a focus timer, and a shelf for files.
- **Teleprompter** under the camera that can follow your voice or your Keynote/PowerPoint notes.
- **Privacy monitor** for the microphone and camera; the notch hides itself from screen sharing.
- **Process watcher** for long-running tools like `xcodebuild`, `cargo` and `ffmpeg`.
- Updates itself (Check for Updates… in the notch menu and Settings → About); `blotch uninstall` cleans up hooks and the CLI link.
- Support Blotch on Ko-fi from Settings → About.
