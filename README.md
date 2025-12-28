# Telegram Automation Software

A standalone Telegram automation platform built using Python and Telethon (MTProto).

## Features
- Multi Telegram USER account support
- Automatic account rotation and cooldown handling
- Auto-discovery and auto-join of PUBLIC Telegram groups/channels
- Keyword-based message forwarding
- Text and media filtering
- Safe Telegram rate limits
- Runs 24x7 on Linux / VPS / Raspberry Pi

## Tech Stack
- Python 3.10+
- Telethon
- Async architecture
- SQLite (default)
- systemd for process management

## Safety Notice
- Uses Telegram USER accounts only
- PUBLIC groups/channels only
- Respects Telegram FloodWait limits
- No bypassing or illegal behavior

## Setup (Basic)
1. Clone the repository
2. Install dependencies from `requirements.txt`
3. Set API_ID and API_HASH in environment variables
4. Run the application

## Disclaimer
This software is intended for educational and automation purposes only.
Users are responsible for complying with Telegram Terms of Service and local laws.