# PS5 Loader GUI

PS5 Loader is a simple Windows GUI to send payloads to a jailbroken PlayStation 5 and view the kernel log over TCP.

## Features

- Send JS/ELF payloads to a PS5 over TCP (default port 50000, configurable in the UI).
- Quick buttons for common payloads (e.g. helloworld, lapse, elf_loader, klog_server).
- Connect to `klogsrv` on port 3232 and display the live kernel log in a separate window.[web:255][web:256]
- Status indicator that checks if the PS5 is reachable on the configured payload port.
- Multi‑language UI (German/English).
- Built‑in update checker for the GitHub releases page.

## Requirements

- Windows 10 or 11 (64‑bit).
- A jailbroken PS5 with a payload listener (Remote JS Server / elf loader) running on the network.[web:255][web:258]
- For running from source:
  - Python 3.11+ (or your installed Python version).
  - `pip install pillow pyinstaller` (Pillow only needed for building the EXE icon).
- For the EXE release: no Python installation require
