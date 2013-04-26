# Sample Patterns for ReSharper #

This repository contains a set of sample Structural Search and Replace patterns for ReSharper. SSR patterns allow you to declaratively add warnings and highlights to ReSharper's code analysis.

The patterns are intended to be edited in ReSharper's SSR dialog, and the .dotSettings file in this repo is not human readable.

You can load this file into ReSharper 8.0 using the Extension Manager. Simply search for "sample patterns". You can edit the patterns via the main Options -> Patterns dialog.

Alternatively, if you want to explore the file in this repo, you can add it as a layer in the Manage Options dialog (this is the manual way of doing what the 8.0 Extension Manager is doing for you. It is also the only way to do this for versions of ReSharper pre-8.0).

Go to the ReSharper menu -> Manage Options -> right click on This Computer -> Add Layer -> Select file. You can edit the file directly by clicking the Edit Layer icon to the right of the new layer. Or you can edit Options from the ReSharper menu and Save To the new layer (just hitting Save will save the changes to the default Smart layer, meaning the changes are saved to the This Computer layer.