Mozilla Firefox added support for screensharing in Firefox 33. The feature is currently only enabled for a small number of whitelisted domains which can be specified in the preferences.
This extension is a [bootstrapped extension](https://developer.mozilla.org/en/Add-ons/Bootstrapped_extensions) that adds and removes PureCloud domains from the screensharing whitelist preference without user interaction.

## building the XPI
```
zip purecloud-screenshare.xpi bootstrap.js install.rdf
```
## License
MPL 2.0

Based on [getScreenMedia](https://github.com/HenrikJoreteg/getScreenMedia), which is based on an [example by Mozilla's Brad Lassey](https://hg.mozilla.org/users/blassey_mozilla.com/screenshare-whitelist/) which is licensed under MPL 2.0
