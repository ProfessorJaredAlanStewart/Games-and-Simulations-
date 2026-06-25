# Games, Simulations & Classroom Tools

Free, open, browser-based tools for students and educators — no account, no sign-in, no cost. Built to be picked up, used, and shared.

**Live site:** https://professorjaredalanstewart.github.io/Games-and-Simulations-/

---

## What's here

| File | What it is |
|------|------------|
| `index.html` | The landing page for the collection. |
| `annotated-bibliography.html` | The Annotated Bibliography Desk (the tool below). |
| `README.md` | This file. |

---

## Annotated Bibliography Desk (APA 7)

Drop in a PDF or Word article and it reads the file, pulls verified citation data, and helps you write your annotation — then exports it however you need. The entire tool is a single self-contained HTML file: the PDF reader, Word reader, and fonts are all baked in, so it works with no internet connection once the page has loaded.

### What it does

- **Reads PDFs and Word files** in the browser and extracts the text.
- **Builds an accurate APA 7 citation** by finding the article's DOI and looking it up in [CrossRef](https://www.crossref.org/), or by searching CrossRef by title. Every field stays editable.
- **Handles seven source types** — journal article, book, book chapter, report, web page, conference paper, and dissertation/thesis.
- **Guides the annotation** with a writing scaffold (summary, evaluative, reflective, or combined), an "insert the abstract" helper for raw material, and a live word counter against your target.
- **Shows in-text citations** (parenthetical and narrative) for each reference.
- **Exports** to Word (`.doc`), **RIS** and **BibTeX** (for Zotero, Mendeley, EndNote), a clean **print** layout, or copy-to-clipboard.
- **Processes a stack at once** — drop several files and work through the queue one at a time.
- **Saves your bibliography on the device** so it survives a refresh.
- **Falls back gracefully** — paste raw text if a file won't read or a network blocks the reader, and fill any field by hand.

### Free and private

- No account, no sign-in, nothing to install.
- Everything runs locally in your browser. Files never leave the device.
- Your saved bibliography is stored only in your own browser (local storage), not on any server.

### One online step

The only feature that touches the internet is the **CrossRef citation lookup** (a free, public, no-key database). Offline, that one auto-fill step is skipped and the tool tells you so — parsing, the annotation scaffold, manual entry, saving, and all exports keep working.

> **A note on AI-assisted writing.** The annotation tools are designed to help you write in your own words. An optional button copies a prompt you can paste into any AI assistant for a first pass, but the result should be revised and made your own. Check your program's policy on AI-assisted writing.

---

## Use it

Just open `annotated-bibliography.html` in any modern browser — double-click the file, or visit the live link above. Works on desktop and mobile.

## Host it yourself (GitHub Pages)

1. Put `index.html`, `annotated-bibliography.html`, and `README.md` in the repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose the `main` branch and the `/ (root)` folder, and save.
4. After a minute, the site is live at `https://<username>.github.io/<repo>/`.

---

## Built with

This tool bundles a few excellent open-source libraries, included in the single HTML file:

- [pdf.js](https://mozilla.github.io/pdf.js/) — Mozilla, Apache License 2.0 (PDF text extraction)
- [Mammoth.js](https://github.com/mwilliamson/mammoth.js) — BSD 2-Clause (Word `.docx` text extraction)
- [Spectral](https://fonts.google.com/specimen/Spectral) and [Inter](https://fonts.google.com/specimen/Inter) typefaces — SIL Open Font License 1.1
- Citation data from the [CrossRef REST API](https://www.crossref.org/documentation/retrieve-metadata/rest-api/)

## License

Free to use, adapt, and share. Add a `LICENSE` file (MIT or Creative Commons works well for classroom resources) if you'd like to make the terms explicit.

---

*Built for students who shouldn't have to pay to do good work.*
