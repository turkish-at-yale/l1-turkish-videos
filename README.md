# L1 Turkish Videos

A single-page site that lists the TURKISH 110 (Level 1) lesson videos by week, streamed from Google Drive.

**Source folder:** https://drive.google.com/drive/folders/1I_B3Jj-pHRDuHQKlswP_DYGC7ApWzD3n

## Updating the content

All content lives in [`data.js`](data.js). Each week has:

- `label` – the heading shown on the page
- `folder` – the Drive folder id for that week
- `videos` – a list of `{ id, title }` where `id` is the Drive file id (from `https://drive.google.com/file/d/<id>/view`)
- `slides` – a list of `{ id, title }` where `id` is the Google Slides id (from `https://docs.google.com/presentation/d/<id>/edit`)

Files must be shared as "Anyone with the link" for playback to work. Commit and push; GitHub Pages redeploys automatically.
