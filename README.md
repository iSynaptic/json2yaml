Description
===================
json2yaml - Fork of yaml2json by bronze1man to go the "other" direction

Feature
====================
* zero config.
* zero install.
* support windows,linux,Mac os,freebsd,netbsd,openbsd,plan9 platform

Usage
====================
### shell
* find the build of you platform
* run `echo '{"a": 1}' | json2yaml` to see result

### read from file save to file
```
cat 1.json | json2yaml > 2.yml
```

Notice
=====================
* if you do not know your mashine is 386 or amd64,you can use 386...
* master branch may rewrite history to save space.
* source branch save the history of source code.

Reference
====================
https://github.com/bronze1man/yaml2json
https://github.com/peter-edge/go-yaml2json
