# cterxn.github.io
**[简体中文](https://github.com/cterxn/cterxn.github.io/blob/main/README.md)**  

PR requirements: appropriate size, runnable and secure.

I do not guarantee that packages are usable and safe, especially those in cterxn/TCUR and cterxn/TCSR.

Please visit this repository and the [project home](https://cterxn.github.io) for the latest announcements, information and updates!

## How to use the cterxn/termuxn repository:

Execute.

`
apt edit-sources
`

Add the following to the source.list file.

`
deb [trusted=yes] https://cterxn.github.io/termuxcn termux extras
`

Then execute.

`
pkg update -y
`

Done!

Note: You can also refer to [the source.list change method at the end of the source.list change tutorial in the UTermux Blog](https://blog.utermux.eu.org/ut/changerepo.html#cterxn), except I'm used to apt edit-sources.

## Contribution notes.

**Never make changes to the termuxcn directory directly, Please Commit the new deb package directly to the repository root directory!**



## Plan to create a new source called TCUR (full name: cterxn/TCUR)

Allows everyone to commit, as long as it is a deb package. I do not do any testing, but may occasionally spot test/use it. The names of all such packages (not deb package names!) should have *TCUR* in them.

## Plan to create src-dir (full name: cterxn/src-dir) source

This repository is just a collection of folders packaged as deb, with source packages inside the folders that need to be compiled and installed by your own hands (so that the installed packages are not under apt's control)

## Plan to create the TCSR (full name: cterxn/TCSR) repository

Package (some of) the scripts (categories) from the TCSR repository organized by cterxn as deb packages via folders and install them in /data/data/com.termux/files/usr/src/ (need to be pre-created). Please go ahead and use/install the script yourself after installing the deb package.

All package names will have *TCSR* in them.
