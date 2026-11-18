# Gene Keys Study

A private study site for the Gene Keys and the Golden Path, in plain language, with all your readings in one place.

## What's inside

- **64 Keys**: Shadow (repressive and reactive), Gift, Siddhi, a short "Secret" phrase, programming partner, codon ring, dilemma and body area for every key, plus a notes box.
- **Golden Path**: the Activation, Venus and Pearl sequences, with every sphere and pathway in order.
- **Lines**: the six line keynotes for all 14 spheres.
- **Codon Rings**: all 21 rings and their keys.
- **My Readings**: a library of your PDF Golden Path readings.
- **Basics**: the core terms explained simply.

## Files

```
index.html               the whole site
.nojekyll                tells GitHub to serve files as they are
readings/                all your PDF readings
readings/readings.json   titles and notes for the library
```

## Put it on GitHub Pages

1. Create a repository on GitHub, for example `gene-keys-study`.
2. Upload everything from this folder, including the `readings` folder (**Add file → Upload files**, then drag the files and the folder in).
3. Go to **Settings → Pages**. Set Source to **Deploy from a branch**, Branch **main**, folder **/ (root)**. Click **Save**.
4. After a minute or two the site is at `https://YOUR-USERNAME.github.io/gene-keys-study/`.

When you update, upload the new `index.html` over the old one and hard-refresh the page (Ctrl+Shift+R, or Cmd+Shift+R on a Mac).

## Adding a new reading

1. Open your repository on GitHub and go into the `readings` folder.
2. Click **Add file → Upload files**, drop in the PDF, and click **Commit changes**.
3. It appears in **My Readings** within a minute or two, titled from its file name.

To give it a nicer title, a person's name or a note, open `readings/readings.json`, click the pencil icon, copy one entry and change it:

```json
{
  "title": "Golden Path Reading",
  "person": "Anna",
  "kind": "Golden Path reading",
  "file": "readings/anna-golden-path-reading.pdf",
  "note": "Reading made for Anna's birthday."
}
```

`kind` sets the colour: `Golden Path reading` (green), `Profile chart` (blue), `Analysis` (red); anything else is grey. Keep a comma between entries. Use file names without spaces, for example `anna-golden-path-reading.pdf`.

## About privacy

On a free GitHub account, a GitHub Pages site is **public**: anyone with the link can open it, including the PDFs. If you want it fully private, keep the folder on your computer instead: double-click `index.html` and everything works offline, including the library.

## Your notes

The notes box and the "reviewed" checkbox save in **your browser only**. They don't sync between devices or get uploaded.

The explanations are simplified summaries written for study, not text copied from the books. Facts like partners, rings, dilemmas and body areas come from Richard Rudd's *Gene Keys*, *The 64 Ways*, *Genius*, *Love* and *Prosperity*.
