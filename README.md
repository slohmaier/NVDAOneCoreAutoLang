# OneCore AutoLang #

OneCore AutoLang was written by Stefan Lohmaier

To build this addon, please visit [building.md]

# Description
This plugin uses Windows One Core voices built in to Windows. It
automaticly uses the correct language for speech, if a voice for
this language is installed in Windows.

This plugin is a modified version of the builtin Windows One Core
Voices synthesizer from NVDA. 

FastText with the language identification model is used to identify
the language for every spolen text and correct the language, if a
voice for the language is installed. The default set language is used
otherwise.

# Usage

The Plugin identifies the languages by the installed Speech packages in Windows. To add or remove languages with their voices use Windows settings:
Windows-Settings -> Languages -> SPeech
The plugin looks for installed lagnuage-speech-packs on start and uses the languages if they are installed.
