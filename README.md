# Netskope Client MSI Parameter Wizard

This project provides a simple HTML/JavaScript-based wizard to help generate installation commands for the Netskope Client MSI package on Windows. It's designed as a convenience tool for IT administrators who need to assemble parameters quickly and reliably.

## Features
- Guided form for entering MSI parameter values
- Auto-generated `msiexec` command output
- Copy-to-clipboard functionality
- Lightweight design (HTML + Bootstrap + vanilla JavaScript)

## Screenshot
<img src="https://i.imgur.com/ttcehFM.png" width="400">

## Usage
1. Clone or download this repository.
2. Open `ns_client_msi_wizard` in your browser.
3. Enter your Netskope parameters as required.
4. Copy the generated command and use it in your deployment script or from the command line.

## Security
**This script is intended for local use only and should not be published or exposed on the public Internet.**

- The page makes a single HTTPS request to load the Bootstrap CSS library, protected with Subresource Integrity (SRI).
- No Netskope tokens or other sensitive information is transmitted externally.
- The Netskope token information is critical security data and must remain private at all times.

## License
Licensed under MIT — free to use, modify, and share, with no warranty.

## Disclaimer
This project is **not affiliated with or supported by Netskope**. It may be incomplete, outdated, or inaccurate. Use at your own risk.
