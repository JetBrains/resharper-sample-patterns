[![obsolete JetBrains project](http://jb.gg/badges/obsolete-flat-square.svg)](https://confluence.jetbrains.com/display/ALL/JetBrains+on+GitHub)

# Sample Patterns for ReSharper

This repository contains a set of sample Structural Search and Replace (SSR) patterns for ReSharper 8 and 9.0 (9.1 will be added after 9.1 has been released). SSR patterns allow you to declaratively add warnings and highlights to ReSharper's code analysis.

The patterns are intended to be edited in ReSharper's SSR dialog, and the .dotSettings file in this repo is not human readable.

You can load this file into ReSharper using the Extension Manager (ReSharper &rarr; Extension Manager). Simply search for "sample patterns". The extension simply adds a settings file as a layer in the Manage Options dialog (ReSharper &rarr; Manage Options). The dialog allows enabling or disabling the settings file, which enables or disables the patterns.

In other words, the sample patterns are stored in a separate settings file - [patterns/patterns.dotSettings](patterns/patterns.dotSettings]. When installed as an extension, the settings file is loaded as a read-only "layer", meaning the settings in the file are merged into the global settings, and available to use. They can be edited, and any changes are stored in the user's settings, overriding the values from the extension. See [this help page](http://www.jetbrains.com/resharper/webhelp80/Reference__Settings_Layers.html) for more details on settings layers.

You can edit the patterns via the main Options &rarr; Patterns dialog page.
