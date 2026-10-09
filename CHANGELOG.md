# Changelog

All notable changes to regionpage-v2 are documented here.

## v2.0.4

### Changed

- Live server status comes from Stuxedo's own status page, [status.stuxedo.net](https://status.stuxedo.net) (`Stuxedo/Status`), instead of Stux.Group's: the servers moved there on 9 October 2026 with their history and slugs, so every badge works as before. The "Live status from" link points there too

## v2.0.3

### Fixed

- The footer's copyright line had a second, hidden copy of the © icon inside its screen-reader text; it's gone, leaving the visible icon and a plain "©" for screen readers. Nothing changes on screen

## v2.0.2

### Changed

- The footer no longer says "Stux.Cloud is operated by Stux Group Ltd."; that belongs on the Imprint, which still says it. The copyright line names Stux.Cloud instead of Stux.Group ("© 2026 Stux.Cloud. All rights reserved.")

## v2.0.1

### Fixed

- The light/dark choice was saved in the browser under `stuxedo-theme`, a name left over from the Stuxedo page this design was built from; it's now `stuxcloud-theme` on every page, and the Cookies Policy names it correctly. Nothing else in this archived design changes

## v2.0.0

### Added

- Archived [StuxCloud/regionpage](https://github.com/StuxCloud/regionpage) at commit `980247b` (`v1.0.1`), the last state before Stux.Cloud's rebrand from two-tone green to single teal, preserving history up to that point as this repository's own `main` branch

### Changed

- Served from `regionpage-v2.stux.cloud` instead of `regionpage.stux.cloud` (CNAME, canonical URLs, sitemap and robots.txt)
- Logo, icon and favicon now point at the archived green assets under `https://global.media.stux.cloud/v2/` instead of the live Stux.Cloud brand assets, which are now teal
- README and CONTRIBUTING describe this repository as an archive
