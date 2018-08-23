# Unity-Speech-Generator

![](https://imgur.com/Yhua6QK.png)

Little tool to quickly generate lines of text using MacOS's `say` commandline tool.

# Why
It's a handy little thing for generating lines of dialogue to use in games, possibly as a placeholder before recordings are made.

# This only works on MacOS!

If you also have [sox](http://sox.sourceforge.net/) installed, it will also convert the audio file (by default `aiff` format) into an mp3, and delete the original.

# How to use

Put the script into an `Editor/` folder in your `Assets/` folder, then go to `Util > Speech Gen` to open up the tool.

The output folder will be in the `Assets/` folder, and will be created if it doesn't exist.
