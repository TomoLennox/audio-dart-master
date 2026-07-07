# Audio Dart Master — sanitized restoration

This directory is a static restoration of the public information pages from the old AudioDartMaster.com backup. It is suitable for GitHub Pages.

## What was preserved

- Public HTML information pages
- Product photographs and logos
- Audio interviews
- Text, Word, and RTF downloads
- The original visible wording and general appearance

## Technical repairs made

- Removed legacy scripts and inline JavaScript event handlers
- Corrected several broken local file paths
- Added document titles/encoding wrappers to old HTML fragments
- Replaced two broken download links with notes that the files were absent from the backup
- Added `.nojekyll` and a simple `404.html`

## Deliberately excluded

The original backup also contained PHP, CGI, server logs, AWStats data, hosting-control files, database configuration, and an old PHP/MySQL online game. These are not compatible with GitHub Pages and were not copied. Several PHP files showed clear signs of a past hosting compromise, so the original backup should not be uploaded to a public repository or web server.

## Missing from the backup

- `images/Andrew_Leibs_interview.mp3`
- `ADM_revisions.txt`

## GitHub Pages

Place the contents of this directory at the root of the `audio-dart-master` repository. In GitHub, open **Settings → Pages**, select **Deploy from a branch**, choose the `main` branch and `/ (root)`, then save.

Do not add a `CNAME` file or change Register.com DNS until the restored site has been tested at the temporary GitHub Pages address.
