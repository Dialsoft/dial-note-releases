# Dial-note

**A plain, simple text editor for Windows 10 and 11 - just like the Notepad that came with Windows 10.** By Dialsoft LLC.

## Download

Dial-note 1.0.0 comes two ways. Both are the same program.

- **[Dial-note-Setup.exe](https://github.com/Dialsoft/dial-note-releases/raw/main/Dial-note-Setup.exe)**: the installer (0.3 MB). Adds Dial-note to the Start menu, to "Open with" for text files, and to Windows "Installed apps", with an uninstaller. It asks whether to install for **just you** (no administrator needed) or for **everyone who uses the PC**.
- **[Dial-note.exe](https://github.com/Dialsoft/dial-note-releases/raw/main/Dial-note.exe)**: the portable copy (0.5 MB). Nothing to install: put it somewhere like your Desktop or `C:\Tools` and double-click it.

**For IT / remote deployment:** `Dial-note-Setup.exe /S` installs silently for the account running it; add `/ALLUSERS` (as administrator) for everyone, `/DESKTOP` for a Desktop shortcut, `/NOOPENWITH` to leave "Open with" alone, and `/NOUPDATES` to switch off automatic update checks.

Windows may show a blue "Windows protected your PC" box the first time: click **More info**, then **Run anyway**.

SHA-256: Dial-note-Setup.exe `1d83ebc09b2ca76280bfd70a7674853a8aa11229d54aa68846f7d505757ecb1d` · Dial-note.exe `7a8efad4be813e95f4755327103d13f867339d86f8cca26a50db6e907ad31b6d`

## What it does

Everything the Windows 10 Notepad does, with the same menus and keyboard shortcuts: New, New Window, Open, Save, Save As (with the Encoding list), Page Setup with header and footer, Print, Undo, Cut, Copy, Paste, Delete, Search with Bing, Find / Find Next / Find Previous, Replace and Replace All, Go To, Select All, Time/Date (F5), Word Wrap, Font, Zoom (Ctrl + mouse wheel) and the Status Bar (Ln, Col, zoom, line endings, encoding). ANSI, UTF-8, UTF-8 with BOM, UTF-16 LE and BE; Windows, Unix and Mac line endings; the .LOG diary trick; Ctrl+Backspace; drag a file onto the window to open it.

Plus: every menu item explains itself in the status bar, every box has detailed tooltips, and Dial-note keeps itself up to date (Help menu).

- **[User Guide](GUIDE.md)** · **[What's new](CHANGELOG.md)** · Website: https://dialsoft.com/dial-note/

© 2026 Dialsoft LLC, Marc Frega, Wharton NJ. Built with Claude by Anthropic.
