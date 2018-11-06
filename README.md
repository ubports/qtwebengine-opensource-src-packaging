# QtWebEngine Packaging

This repository contains the packaging for [QtWebEngine](https://wiki.qt.io/QtWebEngine) for Ubuntu Touch.

## Updating QtWebEngine version

When updating QtWebEngine, be sure to visit [debian/rules](debian/rules) and update the `syncqt.pl` line to generate the SYNCQT headers for the new version of QtWebEngine.
