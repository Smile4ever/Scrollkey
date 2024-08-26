3.1.0 (2024-08-26)
==================
* Upgrade to Manifest V3, make sure that Scrollkey has the necessary permissions to access to the webpages you browse
* Add compatibility for Chrome
* Use build script from Translate Now with slight adaptations
* Remove PNG files from the repository, so that they are not included in the build
* Update repo on GitHub to include all the code for the last version
* Add README to repo

3.0.1 (2019-01-02)
==================
* Fix: if scrolling doesn't work because we are at the end of a page or something, don't cancel the default event
* Fix: don't show notification more than once per tab, unless the scrolling direction changes or the page is reloaded

3.0.0 (2017-11-25)
==================
* Implement optional smooth scrolling (off by default)
* Implement blacklist feature, fixes #29
* Rework options screen - use flexbox instead of table
* Use more generic localisation method
* Phase out setTimeout usage
* Implement scroll to top with gg, scroll to bottom with GG

2.0.1 (2017-09-04)
==================
* Fix "cannot scroll" notification appearing on some sites when scrolling is available by calculating scroll limit differently

2.0.0 (2017-06-24)
==================
* Add notification tips for horizontal/vertical scrolling
* Add notification "Saved preferences" and translation in Dutch
* Replace PNG files by SVG file
* Use sync storage instead of local storage (preferences from local storage are migrated to sync storage)
* Checkboxes now render correctly (workaround for bug https://bugzilla.mozilla.org/show_bug.cgi?id=1354336)
* Rework preferences internally
* Partial support for scrolling inside iframes (same-origin policy limits what Scrollkey can do for other iframes)
* Cleanup

1.1.0 (2017-01-29)
==================
* Update Spanish translation
* Make option window layout better

1.0.2 (2017-01-29)
==================
* Fix optional PageUp and PageDown kidnapping
* Improve scrolling experience for PageUp/PageDown

1.0.1 (2017-01-05)
==================
* Insert at page load start, not when page loading is finished

1.0.0 (2017-01-05)
==================
* Port Scrollkey to WebExtension (requires Firefox >=48).
