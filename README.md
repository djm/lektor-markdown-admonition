# lektor-markdown-admonition

This plugin adds admonition tags to Markdown for Lektor.  This feature is
inspired by the extension in Python Markdown but simplified.

## Enabling the Plugin

To enable the plugin run this command:

```
$ lektor plugins add markdown-admonition
```

## Syntax

A paragraph prefixed with exclamation marks is handled as admonition:

```
! a note

!! an informational message

!!! a tip to users

!!!! a warning
```

They are rendered into `<div class="admonition admonition-note">` and
so forth.
