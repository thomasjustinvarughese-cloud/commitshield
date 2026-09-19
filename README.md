# CommitShield 🛡️

> Automated Git Hygiene & AI-Powered Conventional Commits.

CommitShield is a developer CLI that prevents accidental secret leakage (AWS keys, API tokens, private SSH keys) and generates clean, conventional commit messages directly from your staged diffs.

## Features
- **Zero Leakage:** Scans staged changes against credential regex patterns before commits are applied.
- **Smart Conventional Commits:** Summarizes your diff into clear `feat:`, `fix:`, or `docs:` semantic commit messages.
- **Lightweight:** Single-dependency Python CLI tool.

## Installation & Setup
```bash
git clone [https://github.com/](https://github.com/)<your-username>/commitshield.git
cd commitshield
pip install requests
[https://polar.sh/commitshield/products/commitshield-pro](https://polar.sh/commitshield/products/commitshield-pro)
