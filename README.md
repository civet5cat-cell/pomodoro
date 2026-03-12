# 🍅 Daily Schedule Timer

A minimal, elegant daily schedule timer designed for iPad. Built as a single HTML file — no installation required.

**Live:** [may2cat.github.io/pomodoro](https://may2cat.github.io/pomodoro)

---

## Features

- **Session countdown** — shows remaining time (HH:MM:SS) during active sessions; displays live clock during breaks
- **Floating label** — each character floats independently with a subtle noise animation
- **Ambient glow** — background color shifts to match the current session's color
- **Session transitions** — full-screen flash when a new session begins
- **Stand-up reminder** — configurable interval reminder to move and stretch
- **Sound picker** — 10 synthesized sounds to choose from, with preview
- **Fully customizable** — add, edit, and delete sessions with custom labels, times, and colors
- **Persistent** — all settings and schedule data saved locally in the browser
- **UTC+8 forced** — always displays Beijing time regardless of device timezone or VPN

---

## How to Use

### Add to Home Screen (iOS Safari)

1. Open the link in **Safari**
2. Tap the Share button → **Add to Home Screen**
3. Launch from your home screen for a full-screen experience

### Manage Your Schedule

Tap **⊹ Schedule** (top right) to:
- View and edit existing sessions
- Add new sessions with custom time, label, and color
- Choose a transition / reminder sound
- Toggle stand-up reminders and set the interval
- Enable / disable session transition animations

---

## Sounds

| Name | Description |
|------|-------------|
| Silent | No sound |
| Message | SMS tone |
| Bowl | Singing bowl |
| Mail | Send sound |
| Ding | Crisp single tone |
| Click | Shutter click |
| Chime | Double tone |
| Soft | Gentle tone |
| Low | Deep tone |
| Triple | Ascending tones |

All sounds are synthesized via Web Audio API — no audio files needed.

---

## Tech

- Vanilla HTML / CSS / JavaScript — zero dependencies
- Web Audio API for sound synthesis
- `localStorage` for data persistence
- `WakeLock` API to prevent screen sleep
- Forced UTC+8 time calculation independent of device timezone

---

## Notes

- **Sound** requires the device to not be on silent mode
- **Wake lock** keeps the screen on while the app is active (Safari only)
- Schedule data is stored per browser — clearing Safari data will reset sessions
- Works offline once loaded

---

*Built with Claude · March 2026*
