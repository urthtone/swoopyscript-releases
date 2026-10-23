# SwoopyScript for Windows

This repository only hosts the Windows downloads of SwoopyScript. There is no source code here.

Product page, pricing and support: https://swoopyscript.com

## Download

Open the latest release (the entry that is not marked "Pre-release") and download:

- `SwoopyScript-Setup-<version>-x64.exe`. The installer. Use this one.
- `SwoopyScript-Portable-<version>-x64.exe`. Runs without installing.
- `SHA256SUMS.txt`. The SHA-256 of each file above.

64-bit (x64) Windows. There is no Mac or Linux version.

## First start

1. Run the installer. Windows SmartScreen may say "Windows protected your PC", because these releases are not code-signed yet. Choose More info, then Run anyway.
2. Start SwoopyScript. Choose the 7-day free trial, or choose I have a license key.
3. Each license key works on up to 2 PCs. To move SwoopyScript to another PC, open Help > License on the old one and choose Deactivate this PC first.

## Check your download (optional)

In PowerShell, in the folder you downloaded to:

    Get-FileHash .\SwoopyScript-Setup-<version>-x64.exe -Algorithm SHA256

The result must match the line for that file in `SHA256SUMS.txt`.

## Terms and support

- Terms of sale and license: https://swoopyscript.com/terms
- Support: https://swoopyscript.com/#support
