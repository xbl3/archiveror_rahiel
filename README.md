# Archiveror

[![Build Status](https://travis-ci.org/rahiel/archiveror.svg?branch=master)](https://travis-ci.org/rahiel/archiveror)
[![License](https://img.shields.io/badge/License-GPLv3+-blue.svg)](https://github.com/rahiel/archiveror/blob/master/LICENSE.txt)

Archiveror is a browser extension that archives webpages by submitting them to
<https://archive.is> or <https://archive.org>. These archives are publicly
available, so you then have a backup that you can refer to in case the original
falls prey to [link rot](https://en.wikipedia.org/wiki/Link_rot).

Archiveror will also protect your bookmarks by automatically archiving them in
the background. Its icon will change when you visit a bookmark it has archived,
clicking on it opens the page on the archive. Archiving of bookmarks happens
when you make a new bookmark and when you open an old bookmark. This can be
disabled.

You can manually archive webpages by clicking on the icon or using the Alt+Y
hotkey (configurable). The URL for the archive is then copied to your clipboard,
so you can easily paste the link for references and citations.

Happy archiving!

## Archiving Services

Archiveror supports several online archiving service. You can change which one
to use for manual archiving at the options.

- [**archive.is**](https://archive.is), launched in 2012.
- [**archive.org**](https://archive.org/web/), launched in 2001. Respects
  [robots.txt](robot) so it cannot archive all webpages.

[robot]: https://en.wikipedia.org/wiki/Robots_exclusion_standard

## Local Saving
(Currently for Chrome only)

Archiveror can also make local copies of webpages. One page will be saved in a
single [MHTML](https://en.wikipedia.org/wiki/MHTML) file. Bookmarks will be
saved automatically. Pages can also be manually saved by either clicking the
button or pressing Ctrl+Shift+S.

To enable local archiving, right click the Archiveror button, go to the options
and then pick "Local".

In local archiving mode your bookmarks will be saved in your Downloads directory
following your bookmark structure. If you move your bookmarks around, Archiveror
will mirror your changes and likewise move your local archives. For this to work
you need to check "Allow access to file URLs" at the extensions page. Go to your
extensions and enable it: <https://i.imgur.com/ahrfe3M.png>.

## Installation

* [Chromium](https://chrome.google.com/webstore/detail/archiveror/cpjdnekhgjdecpmjglkcegchhiijadpb)
* [Firefox](https://addons.mozilla.org/firefox/addon/archiveror/)

## Credits

* Both the [floppy disk icon](floppy) and the [star icon](star) are by the
  artist [sixsixfive](https://sixsixfive.deviantart.com/) and were generously
  released into the public domain.
* This extension would not be possible without the free service provided by
  <https://archive.is>.
* The essay [Archiving URLs](http://www.gwern.net/Archiving%20URLs) by Gwern
  Branwen served as inspiration for this add-on.

[floppy]: https://openclipart.org/detail/211780/matt-icons_media-floppy-by-sixsixfive-211780
[star]: https://openclipart.org/detail/212371/rodentia-icons_help-about-by-sixsixfive-212371
