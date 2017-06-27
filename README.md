Suspend Prevent
===============

Debian package source for building `suspend-prevent` a systemd service that keeps a laptop from suspending when plugged into wall power, but allows it while on battery power.

Based on Nicco Di Rocco's blog post at https://nrocco.github.io/2014/06/05/suspend-prevent-systemd.html

To build:

    debuild -i -us -uc -b

The built package is available in the [releases](https://github.com/stuartf/suspend-prevent/releases) of the github repo.
