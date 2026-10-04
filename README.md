# Bubat AI for Windows

An automated forex trading agent for **MetaTrader 5** that runs on your own PC, with a local AI model (no cloud AI, no subscription to an AI service).

## Download

Get **`BubatAI-Setup-<version>.exe`** from the [latest release](https://github.com/syarief02/bubat-ai-releases/releases/latest) and run it. No administrator rights, Python or other tools needed: the installer checks your PC, and on first start Bubat AI downloads the AI engine (Ollama) and the AI models that fit your PC.

**Requirements:** Windows 10 or 11 (64-bit), 8 GB of memory (16 GB recommended), about 25 GB of free disk space, MetaTrader 5 with a **demo account**. An NVIDIA graphics card with 4 GB or more is recommended; without one the AI runs on the processor and trades only the 7 major pairs.

## Free trial and license

Sign in with your Google account in the app to start a **free 7-day trial**. After the trial, new trades pause (open trades are still managed) until you have a license.

**To get a license: email [support@eabudakubat.com](mailto:support@eabudakubat.com) or visit [eabudakubat.com](https://eabudakubat.com).**

## Please read

- **Trading is risky.** The bot can lose money and has lost money in testing. Past results don't predict future results. **This is not financial advice.**
- **Demo accounts only by default.** Bubat AI refuses real-money accounts unless you change a setting by hand.
- During the free trial the bot's trade results are shared with the Bubat AI community database to improve the bot: never your account number, balance or money amounts. See the [Privacy Policy](PRIVACY.md) and the [Terms](TERMS.txt).

## "Windows protected your PC"

The installer is not code-signed yet, so Windows SmartScreen may warn about it. Click **More info**, then **Run anyway**. To check the file is the original, compare its SHA-256 (`Get-FileHash BubatAI-Setup-<version>.exe` in PowerShell) with the `.sha256` file in the release.

## Updates

Bubat AI checks this page for new releases. Each update is verified against its checksum and tested before it replaces the current version, and you can go back to the previous version in Settings.

---
© 2026 Bubat AI · [eabudakubat.com](https://eabudakubat.com) · [support@eabudakubat.com](mailto:support@eabudakubat.com)
