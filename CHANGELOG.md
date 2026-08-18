# Changelog

## Why the numbers restart at 1.0.0

Everything before 1.0.0 was development in this repository, never released and
never installed by anyone but the author. When the mod was submitted to the
Windhawk catalogue the version was reset to 1.0.0, because publishing something
as "4.4.5" implies a history of releases that does not exist.

The 4.x history is still in this repository's git log.

## 1.2.x

- **1.2.1** — Completed the identical-rebuild skip so a taskbar move no longer
  floods the log. A dropped action is logged rather than silent. The dashboard's
  size row clamps against the same rectangle the zone builder uses. Documented
  that Show desktop as a hold is a toggle rather than a true peek, since
  Windows exposes no API for the latter.
- **1.2.0** — Long process paths no longer defeat the exclusion list. The
  dashboard reports effective rather than configured sizes. The Start-menu mask
  extended to actions that do not go through the key-sending path. The settings
  picker, the log and the readme now spell every action identically.

## 1.1.x

- **1.1.9** — Readme restructured around a quick start and the trigger styles.
- **1.1.8** — Fixed a shutdown race that could strand the dashboard thread.
- **1.1.5-1.1.7** — Hold zones release when the mod unloads; a held Win key no
  longer opens the Start menu; edge segments compare their release action
  before merging.
- **1.1.0** — **Hold to peek**: a zone can run one action on arrival and another
  when the pointer leaves, restoring the Show Desktop button Windows 11 dropped.

## 1.0.x

- **1.0.1** — Show desktop now uses Win+D. The documented shell API returns
  success and does nothing on Windows 11 build 26300.
- **1.0.0** — First submission to the Windhawk catalogue.
