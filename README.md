QuickRulers - Sublime Text Plugin
=================================

![No words needed](http://i.imgur.com/lEKwdBc.gif)


## Installation

Use [Package Control][] to [install][] "QuickRulers".

[Package Control]: https://packagecontrol.io/installation
[install]: https://packagecontrol.io/docs/usage


## Usage

Create a key binding
for the `quick_rulers` command,
and use it.

Features live preview
and restore-on-cancel.

Here are two example bindings:

```js
[
  { "keys": ["alt+r"], "command": "quick_rulers" },
  { "keys": ["alt+shift+r"], "command": "quick_rulers",
    "args": {"show_current": false} }
]
```
