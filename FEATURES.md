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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for small business operations:

1. **Zotero** — manage research sources and citations (org.zotero.Zotero)
2. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
3. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
4. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
5. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
6. **Foliate** — read EPUB books (com.github.johnfactotum.Foliate)
7. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
8. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
9. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
