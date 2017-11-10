# XPather

Chrome extension for XPath operations on current document, reliable and easy to use with fully featured XPath 2.0 support.

[![Get it from Chrome Web Store][logo]](https://chrome.google.com/webstore/detail/hjogncmeicjejlbjkmjikegidahpcpmj/publish-delayed)

### Features

- evaluating XPath on current document (using [jQuery XPath](https://github.com/ldilov/jquery-xpath))
- evaluating XPath 2.0 queries and expresions
- matched nodes content preview in sidebar
- functions and attributes shortcuts
- scroll viewport to selected node

### What's new

- Added toggle switch, to toggle between searching xpath by normalizing the input or without normalization. When toggle is on, it uses jquery.expath(xpathSelector), when it is off, it uses jquery.xpath(xpathSelector).
- Added multiline support for the xpath path field.

### Buttons

Floppy button - generates normalized xpath selector from your input
Refresh button - performs a new xpath search (refreshes the result)
Toggle button - used to toggle between normal xpath searching and normalization enabled xpath searching.

### Keyboard shortcuts

<kbd>Alt+X</kbd> - toggle XPather

<kbd>Alt+Shift+X</kbd> - toggle XPather Sidebar (when XPather is active)

<kbd>Alt+Z</kbd> - autocomplete XPather input

All shortcuts are customizable using "Keyboard Shortcuts" option located on the bottom of Chrome extensions page (chrome://extensions).

### Available autocomplete shortcuts

Shortcut | XPath function
--- | --- | ---
`co` | contains()
`sw` | starts-with()
`ew` | ends-with()
`uc` | upper-case()
`lc` | lower-case()
`no` | not()

Shortcut | HTML tag
--- | --- | ---
`d` | div
`s` | span

Shortcut | HTML attribute
--- | --- | ---
`@c` | class
`@h` | href
`@i` | id
`@s` | style
`@t` | title

[logo]: https://developer.chrome.com/webstore/images/ChromeWebStore_BadgeWBorder_v2_206x58.png "Get it from Chrome Web Store!"
