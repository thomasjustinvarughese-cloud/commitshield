# CommitShield 🛡️

> Automated Git Hygiene & AI-Powered Conventional Commits.

CommitShield is a developer CLI that prevents accidental secret leakage (AWS keys, API tokens, private SSH keys) and generates clean, conventional commit messages directly from your staged diffs.

## Features
- **Zero Leakage:** Scans staged changes against credential regex patterns before commits are applied.
- **Smart Conventional Commits:** Summarizes your diff into clear `feat:`, `fix:`, or `docs:` semantic commit messages.
- **Lightweight:** Single-dependency Python CLI tool.

## How to Install & Use
1. Get CommitShield Pro from [Polar](https://buy.polar.sh/polar_cl_Xz7lAHW152SHAX0xhoF0nnRF4O0Cak8h4Q3DI1ghTFA).
2. Download `commitshield.py` and your license key from your Polar receipt.
3. Run the activation command:
   ```bash
   python commitshield.py --activate YOUR_LICENSE_KEY
