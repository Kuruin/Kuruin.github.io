# Notes & Library

Two small, distraction-free tools hosted on GitHub Pages. Everything saves in your browser.

## Notes — `/`

A notes app that formats as you type (`##` heading, `-` list, `[ ]` checklist, `**bold**`). Select text for a format bar; press `Ctrl /` for every shortcut. **Export** downloads `data.json` — commit it to the repo root and it loads on any browser with no saved notes.

## Library — `/library/`

A collection for design resources: inspiration sites, icon packs, fonts, libraries, AI skill files and more.

- **Save** by pasting links (one or many) into the add bar, or pressing `Ctrl V` anywhere on the page. They land in the section you're viewing, or the Inbox.
- **Save from any site** with the "Save to Library" bookmarklet in the sidebar — drag it to your bookmarks bar; it saves the page you're on with its real title.
- **Sort** into 18 sections across Inspiration, Assets, Building blocks, AI workflow and Learning — drag a card onto a section, use the "Move to…" picker on Inbox cards, or pick one in the edit panel.
- **Find** with search (`Ctrl K`, searches every section; Enter opens the top result), tags and sort (newest, A–Z, domain). Grid or list view.
- On a focused card: `E` edit, `S` star, `M` move, `Delete` remove (with undo).
- **Back up** from the sidebar footer, which counts changes since your last backup. It downloads `data.json` — commit it as `library/data.json` to load it anywhere. **Restore** merges and skips links you already have.

Both pages use Inter and share the light/dark setting. The notes editor ([TipTap](https://tiptap.dev)) and toasts ([Sonner](https://sonner.emilkowal.ski)) load from esm.sh, with plain fallbacks if the CDN is unreachable. Site icons in the Library come from Google's favicon service.
