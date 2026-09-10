# Musai Music Maison — Master Production & Operations Specification

These rules govern all Codex work in this repository. Preserve the existing
production site unless the user explicitly requests a specific change.

## Source of truth for page work

- Edit an existing, completed HTML page directly as the basis for any new or
  revised page. Do not rebuild a page from an old template, recollection, or
  an inferred design.
- The current completed standard song page is
  `坪さん歌/いいんじゃないの/index.html`.
- Create every new standard song page by directly basing it on
  `坪さん歌/いいんじゃないの/index.html`.
- Do not change HTML, CSS, JavaScript, layout, navigation, or any other page
  behavior unless the user explicitly specifies that change.

## Song-page requirements

- Put the album return link immediately below Credits, in the form
  `← アルバム名`.
- Do not alter lyrics: preserve their wording, notation, line breaks, and
  repetitions exactly as supplied.
- Do not change, correct, infer, or adjust user-specified lyric timings.
- A song page must reference the album directory's `cover.jpg` via a relative
  path. Do not copy an album cover into a song directory.
- Store each song's MP3 in that song's own directory.

## Repository and publishing safeguards

- The GitHub repository is `musai634/music`; the canonical branch is `main`.
- Preserve the existing GitHub Pages directory structure and `CNAME`.
- Validate changes in the Test Environment before making a commit.
- Do not commit or push before the user has reviewed and confirmed the
  changes.
- Do not make unnecessary changes or unnecessary commits.
