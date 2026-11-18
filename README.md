# wrjventures.com
## Link-in-bio hub

- `/links/`: apps-first page for social bios (noindex). Each store button is tagged from `?src=`, and `PINNED` in its script sets the featured app (or use `?app=`).
- `/tt/` and `/ig/` forward to `/links/?src=tiktok` and `?src=instagram`. To add a channel, copy one of those folders and change the tag.
- Adding an app: add a `<section class="app">` card with `data-ios-id` / `data-play-id` / `data-page`.
