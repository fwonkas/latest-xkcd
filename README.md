# latest-xkcd-cli

![XKCD Number 196](https://imgs.xkcd.com/comics/command_line_fu.png)

This is a small command line shell script that pulls the latest
[XKCD](https://xkcd.com) comic and displays it in the terminal. This is a
silly little project, so it pains me to say that there are _some requirements_.

## Requirements

- macOS.
- [iTerm2](https://iterm2.com) with
  [Shell Integration](https://iterm2.com/documentation-shell-integration.html),
  specifically for the `imgcat` utility
  ([read about it](https://iterm2.com/documentation-utilities.html)).
- [xmlstarlet](https://xmlstar.sourceforge.net/)
- [htmlq](https://github.com/mgdm/htmlq)
- [hxunent (provided by html-xml-utils)](https://www.w3.org/Tools/HTML-XML-utils/)
- [curl](https://curl.se) (this is included by default with macOS)

## Installation

The easiest way to install the required programs is with Homebrew:

```bash
$ brew install xmlstarlet htmlq html-xml-utils
```

You'll also need to install the iTerm2 Server Integrations, which is pretty
straightforward.

## Running

Put `latest-xkcd` somewhere in your `PATH` and run it! Easy-peasy.

https://github.com/user-attachments/assets/40a003a4-0f35-430b-8e8d-63a000ca08cc

