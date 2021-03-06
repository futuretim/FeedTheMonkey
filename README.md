# FeedTheMonkey

<img align=right src="http://jabs.nu/feedthemonkey/feedthemonkey-icon.png" width='256' alt='Icon'>

FeedTheMonkey is a desktop client for [TinyTinyRSS](http://tt-rss.org). That means that
it doesn't work as a standalone feed reader but only as a client for the TinyTinyRSS API
which it uses to get the normalized feeds and to synchronize the "article read" marks.

It is written in C++ with Qt and QML, it also uses Blink to show the contents. You need
to have Qt 5.6 installed to be able to compile and have a account on a TinyTinyRSS server.

## Installation

Download the latest release code from: https://github.com/jeena/FeedTheMonkey/releases/latest

You can compile and install it everywhere Qt is suported, this means on macOS, Windows
and Linux. For ArchLinux I package it and it's available on https://aur.archlinux.org/packages/feedthemonkey/

## Keyboard shortcuts

The keyboard shortcuts are inspired by other feed readers which are inspired by the text editor vi.

`j` or `→` show nex article  
`k` or `←` show previous article  
`n` or `Return` open current article in the default browser  
`r` reload articles  
`F11` full screen  
`1` night mode  
`Ctrl Q` quit  
`Ctrl +` zoom in  
`Ctrl -` zoom out  
`Ctrl 0` reset zoom  

On macOS use `Cmd` instead of `Ctrl`.

## Trivia

This is version 2 of FeedTheMonkey, you can find version 1 which was written in PyQt in the v1 branch
of this repo. My goal is to make this usable on many different targets, for now it is only for
the use on a desktop computer but I'd like to see it on a mobile device too.

## Screenshot

![Feed the Monkey screenshot](http://jabs.nu/feedthemonkey/screenshot.png)

## License

This file is part of FeedTheMonkey.

Copyright 2015 Jeena

FeedTheMonkey is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

FeedTheMonkey is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with FeedTheMonkey. If not, see <http://www.gnu.org/licenses/>.
