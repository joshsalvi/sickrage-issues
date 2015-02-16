**BEFORE OPEN AN ISSUE**
===============
Search the error in the search box.

If you don't find it please follow the guidelines below, otherwise issue will be closed.

IF YOU HAVE UPDATE ERRORS:

Stop SickRage, SSH and enter SickRage folder
```
git remote add upstream https://github.com/SiCKRAGETV/SickRage.git
git fetch upstream
git checkout master / OR git checkout develop
git reset --hard upstream/master / OR git reset --hard upstream/develop
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
 - Link to a copy/paste of your logfile with clear debug info of the error on [PASTBIN](http://www.pastebin.com)

### ENABLING DETAILED DEBUGGING FOR LOGS
1. Shutdown SickRage
2. Edit config.ini and set debug to 1 then save config
3. Start SickRage and wait for error to occure again
