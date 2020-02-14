## Mailspring Updater

Ubuntu & Debian Bash script for installing the latest Debian package version of Mailspring from https://getmailspring.com/.

The script checks the Mailspring [change log](https://raw.githubusercontent.com/Foundry376/Mailspring/master/CHANGELOG.md) for the latest available version
and compares it against the currently installed version. If Mailspring is not installed, yet, or when a newer version is available, then the script downloads
and installs the latest Debian package from getmailspring.com

### Why An Updater Script?

Foundry376 [does not maintain a Debian package repository](https://github.com/Foundry376/Mailspring/issues/999) for Mailspring.
They only publish the latest version of Mailspring to the Snap repository.

However, I find Snap's theme integration with KDE not great at the moment. The mouse cursor for example is comically small on my 4K monitor. The app window looks out of place.
File dialogs look different. If I can avoid it, I try not to install the Snap version of any app.
