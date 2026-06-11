# Tamachick 🐣

A tiny desktop companion for macOS with a fully local AI brain. A 3D chick lives on your desktop: she chats, speaks, watches your screen time, nudges you to take breaks, manages your reminders and calendar, keeps your Mac awake on request — and everything runs on your machine. **Nothing ever leaves your computer.**

## Download

**[Get the latest release →](https://github.com/Oumnya/tamachick-releases/releases/latest)**

Unzip, drag **Tamachick.app** to Applications, open it. The app is signed and notarized by Apple, so it opens with a normal double-click. On first launch she walks you through a one-time ~6.8 GB model download, then click the egg.

## What she does

- **Talks** — chat in a floating bubble or a full Messages-style window, powered by Gemma-4 12B running locally via MLX, with streaming replies and a real voice (Kokoro TTS, pitched into chick register)
- **Acts** — 30+ tools the model invokes by itself: Apple Calendar & Reminders (read and write), timers, keep-Mac-awake, dark/light mode, screenshots, disk/battery/network checks, QR codes, web search, and more
- **Remembers** — persistent conversations, plus long-term facts she saves when you tell her something worth keeping
- **Cares** — screen-time watching (nudges you out of the terminal after too long), daily focus check-ins, an 18:00 recap, and a Tamagotchi-style happiness state: pet her, take your breaks, and she thrives; ignore her and she visibly droops
- **Lives** — hatches from an egg on first launch, wanders the desktop, watches your cursor, does things on her own when idle, sleeps tucked into the screen edge (throw her at a corner!), and dances Thriller when the moment calls for it

## Requirements

- **Apple Silicon Mac** (M1 or newer — the AI runs on MLX)
- macOS 14 or newer
- ~10 GB free disk, 16 GB RAM recommended

## Privacy

Local-only by design: the LLM, TTS, memory, conversations, and care state all live on your Mac. The app talks to the network only for the one-time model download (Hugging Face) and explicitly-invoked tools (weather, public IP, URL shortener, web search).

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/Oumnya/tamachick-releases/issues).
