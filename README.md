# latest-xkcd-cli

![XKCD Number 196](https://imgs.xkcd.com/comics/command_line_fu.png)

This is a small command line shell script that pulls the latest XKCD comic
and displays it in the terminal. This is a silly little project, so it pains
me to say that there are _some requirements_.

## Requirements

- macOS.
- iTerm2 with Shell Integration, specifically for the `imgcat` utility.
- xmlstarlet
- htmlq
- hxunent (provided by html-xml-utils)
- curl (this is included by default with macOS)

## Installation

The easiest way to install the required programs is with Homebrew:

```bash
    $ brew install xmlstarlet htmlq html-xml-utils
```

You'll also need to install the iTerm2 Server Integrations, which is pretty
straightforward.

## Running

Put `latest-xkcd` somewhere in your `PATH` and run it! Easy-peasy.
