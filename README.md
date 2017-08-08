# Notice Me, Senpai!
*Notice Me, Senpai!* is a BetterDiscord plugin that creates a 'Meow' sound when you receive a Direct Message.

## Features
* Creates a 'Meow' sound on your first *unread* message with someone.
* Even works if Notifications are disabled (May be configurable in the future).

## Installation
* Copy to `C:\Users\%USERNAME%\AppData\Roaming\BetterDiscord\plugins` or wherever appropriate for your OS.
* Restart Discord if needed (`Ctrl+R`).
* Enable it in BetterDiscord's preferences

## Frequently Asked Questions
* How do I change the sound?
  - You can change the source in `new Audio()`. This plugin uses a base64 string representation of an ogg file. You can do this conversion at http://dataurl.net.
* How do I adjust the volume?
  - You can add `audio.volume=0.75;`, etc after `audio` is defined.

## Credits
Created by [XFox Prower](https://github.com/XFoxPrower/).
