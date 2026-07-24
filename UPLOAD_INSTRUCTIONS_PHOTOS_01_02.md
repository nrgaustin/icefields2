# Icefields photo update 5.2 — upload instructions

This update adds **156 newly processed still images** from the two iCloud ZIP files.
The site catalog will contain **175 photos total**.

## Upload using GitHub's website

1. Open the root of the `icefields2` repository.
2. Select **Add file → Upload files**.
3. Open the extracted `icefields_photo_update_01_02_github` folder on your PC.
4. Select everything inside it, including the `assets` folder, and drag it to GitHub.
5. In GitHub's preview, verify examples such as:
   - `assets/photos/large/...`
   - `assets/photos/thumbs/...`
   - `assets/data/photos.json`
   - `assets/data/journal.json`
   - `index.html`
6. Commit with the message: `Add Icefields photo batches 01 and 02`.
7. Wait for Pages deployment, then open:
   `https://nrgaustin.github.io/icefields2/?release=5.2`

## Do not delete existing files

This is an additive update. GitHub will add the new image files and replace only the
catalog/data files included here.

## Matching summary

- GPS matched: 148
- Time matched: 6
- Unmatched: 2

Photos matched by time assume Mountain Daylight Time (UTC−6). The editable
`photo_catalog.csv` is included for later captions, photographers, featured status,
or manual corrections.
