# Keepsake — Hybrid Memory Album

Interactive classroom prototype for curated photo stories and a tabletop album experience.

Live website: https://franciscoxia.github.io/keepsake-album/

## Features
- Create photo albums with captions and recorded or uploaded audio.
- Switch between seven demo viewers, select family/friend recipients and authorise tabletop displays.
- Browse the album, play narration, turn pages and bookmark photographs.
- Submit family or friend contributions for owner approval.
- Export/import JSON backups and print a photo book.

## Demo viewers
Emma Chen 1111; Mei Chen 2468; Wei Chen 2469; Lihua Chen 2470; Alex Morgan 1357; Sophie Lee 1358; Daniel Kim 1359.
These public demo PINs simulate viewer access; they are not real authentication.

## Data and devices
Albums, photos and recordings are stored in the current browser with IndexedDB. There is no live cross-device cloud synchronisation. For filming, use the same browser and device when switching roles. To move an existing album from another website or device, export its JSON backup and import via People & devices → Restore a backup. An imported album is a separate copy.

Microphone recording requires HTTPS (or localhost), a supported browser and microphone permission. No build step or server is required. GitHub Pages publishes this repository's main branch from its root.

Sample photo sources are listed in ASSETS.md. Personal browser albums and recordings are not part of this repository.
