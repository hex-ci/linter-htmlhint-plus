# linter-htmlhint+ package
[![Version](https://img.shields.io/apm/v/linter-htmlhint-plus.svg?style=flat-square)](https://atom.io/packages/linter-htmlhint-plus)
[![Status Linux & OSX](https://img.shields.io/travis/hex-ci/linter-htmlhint-plus.svg?style=flat-square&label=Linux%20%26%20OSX)](https://travis-ci.org/hex-ci/linter-htmlhint-plus)
[![Status Windows](https://img.shields.io/appveyor/ci/hex-ci/linter-htmlhint-plus.svg?style=flat-square&label=Windows)](https://ci.appveyor.com/project/hex-ci/linter-htmlhint-plus)
[![Join the chat at https://gitter.im/linter-htmlhint-plus/Lobby](https://badges.gitter.im/linter-htmlhint-plus/Lobby.svg)](https://gitter.im/linter-htmlhint-plus/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A plugin for [Linter] providing an interface to [HTMLHint]. It will be used with files that have the syntax.

Support for ignoring text using custom regular expressions.

If you have new needs, you can write in the issue, thank you.

Fork from linter-htmlhint.

## Installation

The [Linter] package will be installed for you to provide an interface to this package. If you are using an alternative debugging interface that supports linter plugins simply disable [Linter].

```ShellSession
$ apm install linter-htmlhint-plus
```

## Config

This plugin will search for a [HTMLHint] configuration file called `.htmlhintrc` and use that file if it exists in any parent folder. It will stop at the first `.htmlhintrc` file found.

## Settings

You can configure `linter-htmlhint-plus` in Atom's Settings.

[linter]: https://github.com/atom-community/linter "Linter"
[HTMLHint]: https://github.com/htmlhint/HTMLHint "HTMLHint"
