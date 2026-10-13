# Sweetie & You — Birthday Universe ♡

A multi-page-feeling, 10-page romantic birthday experience with:
- Password gate (`1405`) and hint: “You + Me = 4 numbers.”
- Dating-app origin story and a personal “never thought we'd get this close” chapter
- Separate photo slots on multiple pages
- Per-page soundtrack support (10 separate MP3s)
- Interactive quiz, opened letter, photo wall, birthday wishes, and confetti finale
- Responsive mobile + desktop styling

## 1. Add photos
Place your photos in `assets/photos/` with these exact filenames:
- `a` — dating-app beginning / screenshot
- `02-closer.jpg` — a favourite photo of you two
- `03-little-things.jpg` — candid / chat screenshot
- `04-photo.jpg`
- `05-photo.jpg`
- `06-photo.jpg`
- `07-wish.jpg`

If a photo isn't present, the page shows a designed placeholder with the filename to use.

## 2. Add a different song on every page
Put MP3 files in `assets/music/` named:
- `page-01.mp3`
- `page-02.mp3`
- ...
- `page-10.mp3`

Each page plays its own track when entered, where the browser allows playback. Some browsers block automatic audio; the visitor can tap the ♫ button in the top bar to play/pause. Use music you have the right to share. Do not rely on copyrighted commercial songs being hosted in the ZIP.

## 3. Preview
Open `index.html` in a browser. Internet is only needed for Google Fonts; local fallbacks are included.

## 4. Publish free
Unzip the folder, then drag the whole folder to Netlify Drop: https://app.netlify.com/drop
Or upload its contents to a GitHub repository and enable GitHub Pages.

## Important privacy note
This is a front-end password gate, not real security: the password is in the page source and can be inspected by a technical user. It is meant as a cute birthday unlock, not to protect private data. For a personal gift this is usually fine; avoid adding sensitive photos or private information if publishing publicly.
