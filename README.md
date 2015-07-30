**BEFORE YOU OPEN AN ISSUE**
===============
Search for the error in the search box.

If you don't find it please follow the guidelines below, otherwise the issue will be closed.

**IF YOU HAVE ANY UPDATE ERRORS:**

Go to SickRage Settings > General > Advanced > Github and enable this setting:

- [X] Git reset (removes untracked files and performs a hard reset on git branch automatically to help resolve update issues)

**OR**

Stop SickRage, SSH(Linux)/CMD(Windows) and enter SickRage folder
```
git remote add upstream https://github.com/SiCKRAGETV/SickRage.git
git fetch upstream
git checkout master
git branch -u upstream/master
git reset --hard upstream/master
git pull
```

SickRage Bug/Issue Tracker
===============

This repo is dedicated to tracking bugs and issue reports.

### SUBMITTING A BUG/ISSUE TICKET
(DO NOT POST ANYTHING THAT CONTAINS YOUR LOGIN INFORMATION OR API KEY)<br />
Please include the following when opening a new ticket:
 - Branch
 - Commit hash
 - Your operating system and python version
 - What you did
 - What happened
 - What you expected
 - Link to a copy/paste of your logfile with clear debug info of the error on [GIST](http://gist.github.com)

### ENABLING DETAILED DEBUGGING FOR LOGS
1. Open SR interface, go to: General Settings menu > Advanced Settings > Enable DEBUG

Note: Synology users can use WinSCP to gain access/browse to the root where the Sickrage log is located. /volume1/@appstore/sickbeard-custom/var/Logs/sickrage.log

## FAQ

https://github.com/SiCKRAGETV/SickRage/wiki/Frequently-Asked-Questions

## Wiki

https://github.com/SiCKRAGETV/SickRage/wiki
