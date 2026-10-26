# Notes

A minimal, distraction-free notes app hosted on GitHub Pages.

- Formats as you type (`##` heading, `-` list, `[ ]` checklist, `**bold**`); select text for a format bar.
- Notes save in your browser as markdown. Use **Export** to download `data.json`; commit it to the repo root and it loads on any browser with no saved notes.
- Press `Ctrl /` in the app for every shortcut.

Built as a single `index.html`. The editor ([TipTap](https://tiptap.dev)) and toasts ([Sonner](https://sonner.emilkowal.ski)) load from esm.sh; if the CDN is unreachable the app falls back to a plain text editor and built-in toasts.
