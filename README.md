# android-developer.ro

The welcome page of android-developer.ro (2011), a site I set up for a community of Romanian Android developers: one
HTML5 page for phones and desktops (Mobile Boilerplate's meta tags and helpers, a media-query fallback), in Romanian,
that pointed visitors to the forum while it was being prepared. A historical archive, kept read-only: the site's code as
it ran then, not maintained.

## History

| Date | Commit | |
|---|---|---|
| 2011-12-13 | c8f3583 | the SVN repository created (empty) |
| 2011-12-13 | 6d70ffa | the welcome page (`src/website/`) |
| 2011-12-13 | 6d850aa | the page's last changes |

The forum (MyBB 1.6 with its configuration, a third-party application) is left out of the whole history; the page's
links to `./forum/` lead nowhere here.

## How it was built

From the dump of my SVN repository of 2011, turned into git in 2026 (5 commits; the `git-svn-id` lines name
the revisions), the dates kept. The last commit before this README sets LF line endings and indents with spaces.

## Third-party code

jQuery 1.7.1 (MIT), Respond.js (MIT or GPL v2) and the Mobile Boilerplate helper functions (MIT), in
`src/website/scripts/lib/`.

## Licence

MIT (see `LICENSE`), added in 2026: the site named no licence. The logos are mine.

See also my Android archives in [android-2010-2014](https://github.com/webservco-legacy/android-2010-2014) (with the
tutorials of the site).
