# Nseflower [![](https://img.shields.io/github/last-commit/raioramalho/Nseflower.svg)](https://github.com/raioramalho/Nseflower/releases/) [![](https://img.shields.io/github/release-date/raioramalho/Nseflower.svg?style=popout)](https://github.com/raioramalho/Nseflower) [![](https://img.shields.io/github/release/raioramalho/Nseflower.svg?style=popout)](https://github.com/raioramalho/Nseflower/releases) [![Twitter Follow](https://img.shields.io/twitter/follow/raioramalho.svg?style=social&label=Follow)](https://twitter.com/raioramalho)

```
Nseflower v1.0 (https://gitlab.com/raioramalho/nseflower)

Automate scans with nmap script engine (NSE).
This tool has been translated from Portuguese[br] into English[us].
I do not take responsibility for your actions.
This code uses a GPL license.

Usage: nseflower --run <script> -rhost <target> <target especification> <nmap extra options>

Engine Options:
    --run <>: Start the scan with script on target
    --easy <>: Start the old version with easy mode
    --list <type>: List all the scripts or specify the type: smb, ssh, ftp...
    --script-help <script>: Shows help about scripts. For each script matching the given specification
    --script-trace <>: This option does what --packet-trace does, just one ISO layer higher
    --script-updatedb <>: This option updates the script database found in scripts/script.db

