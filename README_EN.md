# cterxn.github.io

**[English](https://github.com/cterxn/cterxn.github.io/blob/main/README_EN.md)**    

Submission requirements: appropriate size, runnable, secure

I do not guarantee that packages are usable and safe, especially those in cterxn/TCUR and cterxn/TCSR

Please visit this repository and the [project home](https://cterxn.github.io) for the latest announcements, information and updates!

Please read the README.md in its entirety before use

## How to use the cterxn/termuxcn repository:

Execute.

`
apt edit-sources
`

Add the following to the source file.

`
deb [trusted=yes] https://cterxn.github.io/termuxcn termux extras
`

Then execute.

`
apt update
`

Done!

Note: You can also refer to [the source change method at the end of the source change tutorial in the UTermux blog](https://blog.utermux.dev/ut/changerepo.html#cterxn), except I'm used to `apt edit-sources`

## Contribution notes.

**Never make changes to the termuxcn directory directly! Commit the new deb package directly to the repository root directory **



## Plan to create a new source called TCUR (full name: cterxn/TCUR)

Allows everyone to commit, as long as it is a deb package. I do not do any testing, but may occasionally spot test/use it. The names of all such packages (not deb package names!) should have *TCUR* in them

## Plan to create src-dir (full name: cterxn/src-dir) source

This repository is just a collection of folders packaged as deb, with source packages inside the folders that need to be compiled and installed by your own hands (so that the installed packages are not under apt's control)

## Plan to create the TCSR (full name: cterxn/TCSR) repository

Package (some of) the scripts (categories) from the TCSR repository organized by cterxn as deb packages via folders and install them in /data/data/com.termux/files/usr/src/ (need to be pre-created). Please go ahead and use/install the script yourself after installing the deb package.

All package names will have *TCSR* in them

## Call for deb package creation

We hope you will help us to create it! (I would like to prioritize checkinstall and install-log, checkinstall will make it easier to generate deb (rpm, slackware installer, etc.), install-log will capture where the software has been installed after compiling and installing it. (These tools will facilitate packaging)

* checkinstall (source code image: https://github.com/cntrump/checkinstall)
(Official website: http://checkinstall.izto.org/)

* php 7.4 (7.3 is also available. Official download page: https://www.php.net/downloads.php

* install-log (Older but useful. The source code is located at https://nxretc.github.io/install-log-cvs.tar.bz2
(If you have to visit the official site, the link is: http://install-log.sourceforge.net/
...... Note: The link to the latest version is no longer available, I got mine from *webpage time machine*, the last version (roughly) was updated on 2003.05.27)

* hashcat, metasploit and sqlmap (@sqlsec recovered the source code from Git's commits, link: https://github.com/sqlsec/termux-sec-packages/.
