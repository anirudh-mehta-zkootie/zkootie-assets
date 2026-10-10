# Zkootie game assets

Art that the Zkootie games download once and keep on the device, so it does not have to ship inside
every app build. Served through jsDelivr from tagged releases, for example:

    https://cdn.jsdelivr.net/gh/anirudh-mehta-zkootie/zkootie-assets@v1/solitaire/felts/halloween-2026-d1-harvest-moon.webp

Layout:

- `solitaire/cards/<deck>/` court cards (J, Q, K per suit); `<deck>-small/` is a 360px copy for the web
- `solitaire/backs/<back-id>.webp` card backs
- `solitaire/felts/<felt-id>.webp` table felts, seamless 1024x1024 tiles
- `solitaire/events/<event-id>/` art for one event (hero, title lettering)

Files are never changed once tagged; a change is a new file name or a new tag.

All rights reserved. These files are public so the games can fetch them; they are not licensed for reuse.
