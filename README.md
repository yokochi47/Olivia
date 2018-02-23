# Olivia binary installer
Here we are releasing the latest legacy version of Olivia until the open-source version reboots.

## Requirements
The installer runs on Linux (x86_64) and Mac OS.

## Install
 `tar xvzf olivia-bin-*-1.x.x.tgz`<br />
 `cd olivia_release`<br />
 `./install.com [directory]`<br /><br />
 The home directory is set to be `[directory]/olivia_home`.

## Release note
- **Feb 22, 2018**: Release v1.17.0
	- Release under Apache License V2.
	- Fix system clash while manipulating peak memo.
	- Fix NMR-STAR v2.1/v3.1 parser for importing assigned chemical shift.
	- Fix a dialog window for exporting external shift table does not appear.
