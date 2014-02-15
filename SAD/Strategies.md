**this file describes strategies for implementing shareroom**

# Craiglists|Stackoverflow mashup (webapp)

* users post what they have and can specify who to share that info to
* users can ask other users (or post a general request) that others can fill in
* users can search for media they want
* system can recommend to users media based on what they and their friends have as well as which media they've been asking for/rated

# FileSystem adapter

* user installs software that attaches itself to FileSys (context menu in Win for example)
* software runs in background and monitors folders/files user specifies (and forwards info about them to other users)
* software creates virtual folder with other user's files/folders (not actual content but rather info about them, 
kind of like a folder with links)
* user can specify (in other users folders) which files they would like/shouldn't be deleted soon
* looks like a good implementation for Win (don't know how this would with *nix)

# GitLike

* commandline utility that lets users interact with system (adding files, looking at other users files, etc)
* would work well for *nix
