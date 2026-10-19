# Built-in features for ledgerleaf-os

Purpose: small business operations

1. **organize work and records** — run ledgerleaf-os-workspace. It creates ~/Documents/ledgerleaf-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run ledgerleaf-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/ledgerleaf-os-session-plans/.
3. **check records and task readiness** — run ledgerleaf-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/ledgerleaf-os-workspace features/ledgerleaf-os-plan features/ledgerleaf-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for small business operations:

1. **KeePassXC** — org.keepassxc.KeePassXC
2. **VSCodium** — com.vscodium.codium
3. **GIMP** — org.gimp.GIMP

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
