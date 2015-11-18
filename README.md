#### BEFORE YOU OPEN AN ISSUE
For FEATURE REQUESTS use [Feathub](http://feathub.com/SiCKRAGE/SickRage)<br/>
For BASIC QUESTIONS go to the [Forum](https://sickrage.tv/forums/) or [IRC](https://kiwiirc.com/client/irc.freenode.net/?theme=basic#sickrage-issues)

DO NOT POST ANYTHING THAT CONTAINS YOUR LOGIN INFORMATION OR API KEY<br />

Please include the following when opening a ticket :
 - Branch
 - Commit hash
 - Your operating system and python version
 - What you did
 - What happened
 - What you expected
 - How can we reproduce your issue
 - Include a link with your [log file](https://github.com/SiCKRAGE/sickrage-issues/wiki/FAQ's-and-Fixes#enable-debug-for-logs). (Not just a few lines!) And that has the error. Use [GIST](http://gist.github.com) or [Pastebin](http://pastebin.com/)

#### Many issues can simply be solved by:

- Making sure you update to the latest version. 
- Have you tried turning your device off and on again?
- Using the **search** function to see if this issue has already been reported/solved.
- Do a [GIT reset](https://github.com/SiCKRAGE/sickrage-issues/wiki/FAQ's-and-Fixes#update-problems-try-this)
- Checking the [ [Wiki] ](https://github.com/SiCKRAGE/sickrage-issues/wiki) for 
[ [Guides] ](https://github.com/SiCKRAGE/sickrage-issues/wiki/Installation-&-Configuration-Guides)
[ [FAQ'S] ](https://github.com/SiCKRAGE/sickrage-issues/wiki/FAQ%27s-and-Fixes) 
[ [Main settings] ](https://github.com/SiCKRAGE/sickrage-issues/wiki/Settings-explained) 
[ [Show settings] ](https://github.com/SiCKRAGE/sickrage-issues/wiki/Show-settings-explained) 
[ [Remaining settings] ](https://github.com/SiCKRAGE/sickrage-issues/wiki/Remaining-settings-explained) 
- Shutting down SickRage and removing the `cache/mako` & `cache/sessions` folders.
- If SickRage doesnt find any episodes you probably need to : 
 - add a [Scene Exception](https://github.com/SiCKRAGE/sickrage-issues/wiki/Scene-exceptions-and-numbering) 
 - Set the [Default Episode Status](https://github.com/SiCKRAGE/sickrage-issues/wiki/FAQ%27s-and-Fixes#newly-aired-shows-are-not-downloading-and-set-to-skippedignored) to `WANTED`
 - Make sure you understand how [quality detection](https://github.com/SiCKRAGE/sickrage-issues/wiki/Quality-Settings#quality-detectiondetermination) works during searches. 
 - Shutdown SickRage and remove the `cache.db` file
- If you use a QNAP and have SSL errors try this [package](http://apps.qnap.community/11-community/17-qsickrage).
- If you have a `'ascii' codec can't encode character` error, than set your Locale to [UTF-8](https://github.com/SiCKRAGE/sickrage-issues/wiki/FAQ%27s-and-Fixes#i-have-problems-with-special-characters-%C3%A9-etc-what-can-i-do)



