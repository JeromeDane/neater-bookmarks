# Neater Bookmarks

A neat bookmarks tree popup extension for Google Chrome. Licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php).

Translation help is welcomed through [WebTranslateIt](https://webtranslateit.com/en/projects/4222-Neater-Bookmarks).

Originally developed by Lim Chee Aun, http://cheeaun.com/.

# FAQ

### Can I resize the width and height of the popup?

For the width, yes, by dragging on the left (or right for RTL systems) edge of the popup. For the height, no, because it resizes automatically based on the bookmarks displayed. Note that Google Chrome sets a maximum limit on the popup width and height, so it may not expand that far for high resolution screens.

### Why not use a better (more native-looking) toolbar icon?

There is a difference between Chrome's default toolbar icons and extension's toolbar icon. Chrome's icons are basically simple glyphs and shapes to indicate the purpose of the toolbar action. They are simple and dynamic, in a way that can change colors based on the current theme applied. As for extensions, the icon doesn't just indicate purpose but is also a form of branding which sets it apart from all the other extensions. Also, extension icons are not dynamic and don't change based on the theme applied. So, if the extension icon contains just one color (black or dark gray, like the default icons), it won't be able to adapt when you choose a theme with totally different colors. However, Neater Bookmarks provides a way to replace the default toolbar icon with a custom one in the Options menu.

### Sidebar instead of popup please?

Check out [this issue](http://crbug.com/51084).

### Is there a keyboard shortcut to open Neater Bookmarks (popup)?

Currently, there's no way to implement it. Check out [this issue](http://crbug.com/27702).

### Does Neater Bookmarks support Google Bookmarks?

No. There are no plans to support it, because it's lacking an official public API and Chrome already has its own bookmarks system with Sync. There are several existing Chrome extensions that support Google Bookmarks.

### How do I report bugs or suggest features?

Preferably via the [issue tracker](https://github.com/evanshultz/neater-bookmarks/issues). [Email](neaterbookmarks@gmail.com) is OK as well. If you're reporting bugs, please include at least the version/build of Chrome and your OS.

### Why isn't this built into Google Chrome by default?

No idea. That's why Neater Bookmarks exists.

# Technical Details

Neater Bookmarks was powered by [MooTools](http://mootools.net/), but is now powered by Neatools, a custom-coded smaller subset of MooTools. [CodeMirror](http://codemirror.net/) is used for the Custom CSS section.

# Additional Credits

Thanks to [Vyacheslav Grischuk](https://plus.google.com/102311113806447158021) for posting the popup scrollbar fix [here](https://chrome.google.com/webstore/detail/pnbmhmngmdppipkoognikjonljicbhnl/reviews).