Osx-Env
=======

In OSX Yosemite the old methods of setting environment variables for
GUI applications no longer work.  This directory contains a property
list file that calls a script that launches launchctl to set the
environment.

To use this, check out this repository into and copy the file
`com.xantira.loginscript.plist` into your folder
`~/Library/LauncAgents`.  Modify the path in this file to point to the
`Osx-Env` directory, modify the value of `PATH` in `setenv.sh` to the
desired value, log out and log in again.

