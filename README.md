# Introduction

```
➜  source git:(master) ✗ npm install -g gitbook-cli
/Users/mingyi/.nvm/versions/node/v13.14.0/bin/gitbook -> /Users/mingyi/.nvm/versions/node/v13.14.0/lib/node_modules/gitbook-cli/bin/gitbook.js
+ gitbook-cli@2.3.2
added 578 packages from 672 contributors in 11.137s

 ➜  gitbook gitbook init
Installing GitBook 3.2.3
...
warn: no summary file in this book
info: create README.md
info: create SUMMARY.md
info: initialization is finished

➜  gitbook gitbook build
info: 7 plugins are installed
info: 6 explicitly listed
info: loading plugin "highlight"... OK
info: loading plugin "search"... OK
info: loading plugin "lunr"... OK
info: loading plugin "sharing"... OK
info: loading plugin "fontsettings"... OK
info: loading plugin "theme-default"... OK
info: found 1 pages
info: found 0 asset files
info: >> generation finished with success in 0.4s !

➜  gitbook gitbook serve
Live reload server started on port: 35729
Press CTRL+C to quit ...

info: 7 plugins are installed
info: loading plugin "livereload"... OK
info: loading plugin "highlight"... OK
info: loading plugin "search"... OK
info: loading plugin "lunr"... OK
info: loading plugin "sharing"... OK
info: loading plugin "fontsettings"... OK
info: loading plugin "theme-default"... OK
info: found 1 pages
info: found 0 asset files
info: >> generation finished with success in 0.3s !

Starting server ...
Serving book on http://localhost:4000
```

* `gitbook build`
* `gitbook --port 4000 serve ./`
* `test`

ref:

* [setting](http://gitbook.zhangjikai.com/settings.html)
* [Templating](https://snowdreams1006.github.io/gitbook-official/en/templating/)
* [Theme](https://snowdreams1006.github.io/gitbook-official/en/themes/)
