# PS5 Loader GUI

PS5 Loader is a small Windows GUI to send payloads to a jailbroken PlayStation 5 and view the kernel log over TCP.

## Features

- Send JS/ELF payloads to a PS5 over TCP (default payload port 50000, configurable in the UI).
- Quick buttons for common payloads (e.g. helloworld, lapse, elf_loader, klog_server).
- Connect to `klogsrv` on port 3232 and display the live kernel log in a separate log window.
- Status indicator that checks if the PS5 is reachable on the configured payload port.
- Multi‑language UI (German/English).
- Built‑in update check that links to this GitHub repository.

## Requirements

- Windows 10 or 11 (64‑bit).
- A jailbroken PS5 with a payload listener running in your network (Remote JS / ELF loader) and optional `klogsrv` for kernel logs.
## Usage

1. Start `PS5_Loader.exe`.
2. Enter your PS5 IP and payload port (default 50000).
3. Select a payload file or use one of the quick‑payload buttons.
4. Click **Send payload** to deliver it to the console.
5. (Optional) Enter the KLog port (default 3232) and click **Connect KLog** to view the live kernel log.
