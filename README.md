# NGLG-AITHSH

Αίτηση Εισδοχής / Υιοθεσίας / Επαναφοράς — a standalone HTML application form.

## Live page

**https://dskiad.github.io/NGLG-AITHSH/**

(Served via GitHub Pages from the `main` branch.)

## Contents

- `index.html` — the application form.
- `library.html` — **Skiad Repo**, a library-themed page with 12 shelves of
  10 book covers each. Every shelf's genre and every book's title is
  editable in place, and each book can be pointed at a GitHub/code
  repository link, a website link, a Google Drive/Photos link, an
  uploaded photo, or an uploaded PDF — clicking a book opens whatever
  it's linked to. Edits and uploads are saved automatically in the
  browser (IndexedDB), per-device. Open it directly or visit
  `https://dskiad.github.io/NGLG-AITHSH/library.html` once merged to `main`.

## Local preview

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server
```

Then visit `http://localhost:8000`.
