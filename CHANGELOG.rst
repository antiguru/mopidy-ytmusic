*********
Changelog
*********

v0.3.3
========================================

- update poetry install.
- install cleo in build workflow
- Bump pytube version requirement for #41 & #45

v0.3.2
========================================

- Update PyTube v11.0.1 to fix #32 (thanks @stuartf)

v0.3.1
========================================

- update to latest ytmusicapi
- Fix badge alt text in README.rst

v0.3.0
========================================

- more improvements to release automation.
- Added exception handling to _get_youtube_player
- Prevent CHANGELOG entries  for "Merge branch 'master'" commits.
- Fix typo in release.yml
- Update release.yml to skip PYPI upload if there is no token and to use default GH token
- Add GitHub Actions yaml for automating releases.
- Add missing linefeed.
- Merge branch 'master' of https://github.com/OzymandiasTheGreat/mopidy-ytmusic
- switch descramble routines from youtube-dl to pytube
- Merge branch 'master' of github.com:OzymandiasTheGreat/mopidy-ytmusic
- Merge branch 'master' of github.com:OzymandiasTheGreat/mopidy-ytmusic
- Merge branch 'master' of github.com:OzymandiasTheGreat/mopidy-ytmusic
- Merge branch 'master' of github.com:OzymandiasTheGreat/mopidy-ytmusic
- Merge branch 'master' of github.com:OzymandiasTheGreat/mopidy-ytmusic
- - Version bump

v0.2.4
========================================

- Update to ytmusicapi v0.17.2 to handle new changes.
- Lots of rewrites to work around new google changes.

v0.2.3
========================================

- Bug fixes for Iris
- (barely functional) support added for shoutcast

v0.2.2
========================================

- Update to ytmusicapi v0.14.0 to fix search issues.
- added "mopidy ytmusic reauth" convenience command.
- fix for attempting to scrobble tracks from other backends.


v0.2.1
========================================

- Added support for the get_images() library provider.
- Work-around for race condition when Google updates the javascript player.
- Improved support for listening to uploaded music.


v0.2.0
========================================

- Updated to only use Youtube-DL to decode the url's signature to improve speed (Youtube-DL has a lot of overhead). This also means direct access to premium stuff without having to setup authentication for YDL as well.
- Added stream quality preferences.
- Added scrobbling to YouTube Music so that play history would be updated.
- Used mopidy-gmusic code to handle timer events, and proper scrobbling.
- Split code into individual source files per class. library.py is still huge.
- Added auto playlists / mood & genre playlists / subscriptions to Library Browser.
- Added options for more stuff.
- Added support for unauthenticated access to YouTube Music.
- changed "ytm" uri scheme name to "ytmusic" for better legibility.
- also changed uris from HTTP GET style to just colon separated to be more like mopidy-gmusic and so it would interact with existing frontends easier.
- used dephell to generate setup.py from pyproject.toml just so github could parse dependencies.


v0.1.2
========================================

- Minor fixes.
- Updated compatibility with latest versions of ytmusicapi
- Removed ability to list uploads since youtube-dl can't handle them anyway.


v0.1.1
========================================

- Minor fixes.


v0.1.0 (UNRELEASED)
========================================

- Initial release.
