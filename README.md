github-real-icons
=================

This userstyle replaces GitHub’s font-based icons with real PNGs.

Deprecation notice
------------------

I have abandoned this idea because of maintenance burdens.

The motivation for this style was:

* Many web designers replace the body text font face with a web font. This makes text hard to read.
* *Therefore*, block web font downloads or configure the browser to disregard all font faces specified by sites.
* *But*, some sites use web fonts for icons. These include GitHub.
* *Therefore*, write this userstyle.

This used to work except for two points:

* Whenever GitHub adds an icon, the style needs to be updated. The process is non-trivial.
* The number of sites that (1) use icon fonts and (2) are too useful to ignore is rising. It is no longer feasible to prepare a userstyle for each.

There are alternative ways to avoid designer typefaces:

* [Document Font Toggle][dft] puts a button on the toolbar that can be toggled to allow or disallow site fonts. Additionally, it has a configurable whitelist of sites that are always allowed to specify fonts.
* [AdBlock Plus][abp] can block web fonts that are not embedded in CSS as `data:` URLs. One can then add exceptions for known icon fonts.
* Using [Stylish][sty], one can [selectively replace fonts][1] commonly used by designers with a locally installed font.

[dft]: https://addons.mozilla.org/en-US/firefox/addon/document-font-toggle/
[abp]: https://adblockplus.org/en/firefox
[sty]: https://addons.mozilla.org/en-US/firefox/addon/stylish/
[1]: https://adblockplus.org/forum/viewtopic.php?p=100334#p100334
