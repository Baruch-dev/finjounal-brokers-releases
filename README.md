# FinJounal Brokers: downloads

The workstation terminal for brokerage teams, built for African markets.

This repository only hosts the **release files**. The app's source code is private.

## Windows

1. Open the [latest release](../../releases/latest).
2. Download **`FinJounalBrokers-Setup.exe`** and run it. (Prefer no installer? Download
   **`FinJounalBrokers-windows-x64.zip`**, unzip it anywhere, and run `finjounal_brokers.exe`.)

Requires Windows 10 or 11, 64-bit.

### First-run warning
Windows SmartScreen may say **"Windows protected your PC / unrecognized app"** the first time.
The installer is not code-signed yet. Choose **More info -> Run anyway**. You can confirm the file is
untouched by comparing its SHA-256 with `SHA256SUMS.txt` on the release page:

```powershell
Get-FileHash .\FinJounalBrokers-Setup.exe -Algorithm SHA256
```

## Mac, iPhone and iPad
FinJounal Brokers for Mac, iPhone and iPad is distributed through the App Store.

## Help
https://finjounal.com/support
