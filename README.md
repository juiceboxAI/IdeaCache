[README.md](https://github.com/user-attachments/files/23539938/README.md)
# IdeaCache

IdeaCache is a single‑file, dark‑mode note pad that runs entirely in your browser. It stores everything locally (no network calls, no backend) and gives you quick controls for typography, colors, and multiple note tabs—perfect for keeping a pinned browser tab as your personal scratchpad.

## Features
- **Rich yet minimal UI** – Adjustable text color, background color, font family, and font size without leaving the page.
- **Multiple tabs** – Create, rename (double‑click a tab), or delete notes. Each tab has its own content, saved in `localStorage`.
- **Plain-text workflow** – Pasting strips formatting automatically to clean up copy/paste data; Tab key inserts actual tab characters inside the editor.
- **Offline persistence** – Notes, styling choices, and active tab survive refreshes thanks to local storage.
- **One-click export** – “Save as text” downloads the current tab as a timestamped `.txt` file.

## Getting Started
1. Double-click `ideacache.html` (or drag it into a browser) to open the notepad locally.
2. Leave the tab open for quick access; IdeaCache autosaves while you type.
3. Use the top controls to change colors, fonts, or font size. These settings apply to all tabs.
4. Use the tab strip to create or switch between notes. Double-click a tab name to rename it and use the × button to delete it (with confirmation).
5. Click **Save as text** whenever you want a local `.txt` export of the active note.

## Keyboard Tips
- **Tab key** inserts a tab character instead of moving focus.
- **Ctrl/Cmd + V** pastes plain text only, helping you clean up formatted content.

## Development Notes
IdeaCache is intentionally dependency-free. All styling and logic live inside `ideacache.html`, so no build step is required. If you tweak the file, just refresh the browser tab to see changes.

## Version Control
This is version 1.02
