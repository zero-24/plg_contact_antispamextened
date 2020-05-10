# AntiSpamExtended Plugin

This Joomla Plugin implements an additional Anti-spam Protection Layer to your Joomla Contact Forms by allowing you to block any non ascii chars or banned words / chars

## Sponsoring and Donation

You use this extension in an commercial context and / or want to support me and give something back?

There are two ways to support me right now:
- This extension is part of [Github Sponsors](https://github.com/sponsors/zero-24/) by sponsoring me, you help me continue my oss work for the [Joomla! Project](https://volunteers.joomla.org/joomlers/248-tobias-zulauf), write bug fixes, improving features and maintain my extensions.
- You just want to send me an one-time donation? Great you can do this via [PayPal.me/zero24](https://www.paypal.me/zero24).

Thanks for your support!

## Features

This Joomla Plugin allows you to protect you joomla contact form by allowing you to:
- block any non ascii chars
- whitelist allowed non-ascii chars
- maintain a blacklist of not allowed words / chars

## Configuration

### Initial setup the plugin

- Download the latest version of the plugin: https://github.com/zero-24/plg_contact_antispamextended/releases/latest
- Install the plugin using Upload & Install
- Enable the plugin form the plugin manager

Now the inital setup is completed and the default protection is enabled.

### Options

#### Custom Blacklist

A comma-separated list of characters and words to be blocked.

#### Character Whitelist

A comma-separated list of additional characters that should be allowed.

## Translations

This plugin is translated into the following languages:
- de-DE by @zero-24
- en-GB by @zero-24

You want to contribute a translation for an additional language? Feel free to create an Pull Request against the master branch.

## Update Server

Please note that my update server only supports the latest version running the latest version of Joomla and atleast PHP 7.0.
Any other plugin version I may have added to the download section don't get updates using the update server.

## Issues / Pull Requests

You have found an Issue or have an question / suggestion regarding the plugin, or do you want to propose code changes?
[Open an issue in this repo](https://github.com/zero-24/plg_contact_antispamextended/issues/new) or submit a pull request with the proposed changes against the master branch.

## Beyond this repo

This plugin is based on my [[WBB] Anti-Spam Extended](https://github.com/zero-24/wbb-antispam-extended) plugin for the woltlab forum.

## Joomla! Extensions Directory (JED)

This plugin can also been found in the Joomla! Extensions Directory: [AntiSpamExtended by zero24](https://extensions.joomla.org/extension/antispamextended/)

## Release steps

- `build/build.sh`
- `git commit -am 'prepare release AntiSpamExtended 1.0.x'`
- `git tag -s '1.0.x' -m 'AntiSpamExtended 1.0.x'`
- `git push origin --tags`
- create the release on GitHub
- `git push origin master`
