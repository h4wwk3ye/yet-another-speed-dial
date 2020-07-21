# yet-another-speed-dial

A modern speed dial for Firefox and Chrome, inspired by Opera

- Respects your privacy. Unlike other speed dial addons, there is no tracking.
- Automatically generates thumbnails and screenshots, or select your own.
- Uses the browser's native bookmarks library so speed dials can be synced.
- Sortable with drag and drop
- Folder support
- Simple and fast UI

![alt tag](https://github.com/conceptualspace/yet-another-speed-dial/raw/master/assets/screenshot.png)

<a href='https://addons.mozilla.org/en-US/firefox/addon/yet-another-speed-dial/'><img alt='Get it for Firefox' src='https://github.com/conceptualspace/nightlight/raw/master/assets/ff-badge.png'/></a> <a href='https://chrome.google.com/webstore/detail/yet-another-speed-dial/imohnlganmafcmidafklgkgfgaagiohn'><img alt='Get it for Chrome' src='https://github.com/conceptualspace/nightlight/raw/master/assets/chrome-badge.png'/></a>

---

### Changes done by me

- Changed every modal background from white to black. Looks better tbh
- Removed center flex alignments of tile
- Added cursor:pointer to few places
- Moved clock to the bottom
- Added opacity to each tile to give a hover effect

### building for chrome vs firefox

chrome: remove `chrome_settings_overrides` and `browser_specific_settings` manifest keys  
firefox: no changes are required
