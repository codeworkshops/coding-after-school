
# Build Instructions

Instructions to build CodeWorkshops or other Gitbooks.

- Published book: <https://codeworkshops.gitbooks.io/coding-after-school/>
- Github Repo: <https://github.com/codeworkshops/coding-after-school>


## Running Gitbook on Local desktop

<https://toolchain.gitbook.com/setup.html>


### Install gitbook-cli on local machine 

`$ npm install gitbook-cli -g`

Once installed, typing...

`$ gitbook --version`

would show

```
	CLI version: 2.3.2
	GitBook version: 3.2.3
```

### Gitbook Plugins

Use gitbook plugins <https://plugins.gitbook.com/> for your book

** If the `book.json` includes any plugin then `gitbook install` would install required plugins

The following lists the `asciidoc-adminition-icons` plugin installation.

```
$ gitbook install
info: installing 1 plugins using npm@3.9.2 
info:  
info: installing plugin "asciidoc-admonition-icons" 
info: install plugin "asciidoc-admonition-icons" (*) from NPM with version 1.1.0 
info: >> plugin "asciidoc-admonition-icons" installed with success 

```

### Serve gitbook locally 

```
$ gitbook serve .
Live reload server started on port: 35729
Press CTRL+C to quit ...

info: 8 plugins are installed 
info: loading plugin "asciidoc-admonition-icons"... OK 
info: loading plugin "livereload"... OK 
info: loading plugin "highlight"... OK 
info: loading plugin "search"... OK 
info: loading plugin "lunr"... OK 
info: loading plugin "sharing"... OK 
info: loading plugin "fontsettings"... OK 
info: loading plugin "theme-default"... OK 
info: found 14 pages 
info: found 3 asset files 
warn: "sections" property is deprecated, use page.content instead 
info: >> generation finished with success in 2.2s ! 

Starting server ...
Serving book on http://localhost:4000

```

### Where to host gitbook

- can host on gitbook.io
- netlify.com
- Amazon AWS S3 website hosting
