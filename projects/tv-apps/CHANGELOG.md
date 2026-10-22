# Vertex TV release history

Application changes and validation are recorded here. Operational logs, credentials, deployment settings and private library details remain outside this repository.

## Samsung 0.1.22 / LG 0.1.8 — 22 October 2026

- Added Jellyfin profile pictures to the account chooser. Preserve image tags at sign-in/startup/switching, refresh existing saved profiles through their own sessions, and request the tagged user-image endpoint through the authenticated artwork pipeline.
- Keep initials when a profile has no picture or its image cannot load. No new login is needed for previously remembered profiles.
- Make Up from Home's upper controls enter the navigation at Home consistently, independent of horizontal position. Left/Right navigation and shelf traversal remain available.
- Validation: 82 shared tests, five LG compatibility checks, shared-source and compiled-LG browser checks for pictures/fallback/focus, plus existing resume and Up Next browser checks. Verified picture availability through read-only Jellyfin requests.
- Installed and independently verified on both Samsung TVs and the LG. No active Vertex playback was interrupted; aerial Live TV stayed on the LG. The new builds load at the next normal app opening. Physical remote confirmation and sign-in retention remain pending.
- Expanded the media-client and launcher case studies with the shared-source architecture, platform packaging, older-LG adaptations, API integration and deployment checks.

## LG 0.1.7 — 22 October 2026

- Deployed the current homepage, in-player Up Next, Continue watching options and Back-button behaviour to the LG webOS port.
- Retained the LG playback compatibility policy and older-browser adaptations.
- Five compatibility checks and compiled-build homepage browser checks passed; installed version and packaged-file hashes were verified.
- Installed without launching Vertex or disturbing aerial Live TV. The update loads on the next normal app opening; physical playback and sign-in retention remain to be checked.

## Samsung 0.1.21 — 22 October 2026

- Organised Home into Continue watching / Up next, Specials & bonus episodes, Recently added, Film collections and one daily discovery row, below the featured film.
- Added larger headings, theme-coloured accent lines, section spacing and two-line landscape titles.
- Combined Season 0 episodes with selected specials stored as films, suppressing duplicates. Omitted empty sections and collections.
- Added profile-scoped, paginated catalogue selection and populated discovery choices; browsing does not reshuffle on a timer.
- Installed on both Samsung televisions after checking neither was playing an episode. LG deployment remains separate.
- Validation: 80 passing shared tests; actual-app browser checks for row order, navigation, heading visibility, collection contents, absent/failed sections and existing player/resume behaviour. Physical homepage confirmation pending.

## 0.1.20 — 22 October 2026

- Back closes visible playback controls before it exits the player. Nested dialogs close first, and held-key repeats cannot trigger a second exit.
- Kept the explicit Close player action.
- Installed on both Samsung televisions. Back-button behaviour confirmed by the user on a physical TV; browser checks covered paused playback and nested dialogs.

## 0.1.19 — 22 October 2026

- Added a hold-OK menu to Continue watching, with an item-details fallback.
- Clearing resume updates the current user's saved position on Jellyfin. Optional actions mark the item watched or unwatched. Position-only changes preserve watched state, favourites and play count.
- Tile removal waits for server confirmation; failures retain the item and menu. Browser checks cover persistence, profile isolation, short/long presses and focus recovery.
- Sign-in loss was reported following an update and restart. The cause remains unconfirmed; no session-retention fix is claimed.

## 0.1.18 — 22 October 2026

- Moved Up Next into a top-right playback overlay during the final 30 seconds.
- Countdown follows media time; Play next stays inside playback, and Keep watching suppresses automatic progression for that episode.
- Retained the autoplay preference. Tests cover late lookup, duplicate actions, dismissal and player transitions.

## Earlier work — 20–21 October 2026

- Featured films, collection browsing, remembered profiles and remote-friendly settings.
- Centred icon playback controls, catalogue pagination and artwork loading that prioritises visible cards.
- Cache cleanup between tabs and explicit refresh instead of automatic idle homepage rebuilding.
- LG webOS port with compatibility adjustments and a separate playback-conversion policy; Samsung video-copy protection remains for films and episodes.

[Vertex TV case study](vertex-tv.md) · [Television apps](README.md)
