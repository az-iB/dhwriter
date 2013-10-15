# Welcome to the OERPUB fork of the Aloha Editor

We are adapting the Aloha editor for creating books, textbooks and other structured content. We are adding mathematics editing and 
the ability to add educational features like examples, exercises, equations, and glossary entries.   

**Demos:** Thanks for checking us out! You can play with some of our demos by going to our [Demo Page](http://oerpub.github.io/Aloha-Editor/)

**Plugins:** Development is done in branches off of `master`, which are then tested on the `dev` branch, specifically in the [Plugins](src/plugins) directory.

**Quickstart:** To get a development enviroment set up quickly and start working on the editor, 
use the [following instructions](quickstart.rst). The instructions are for Ubuntu using nginx as the webserver, but you can of course use apache or if you have a mac
the webserver that is already present.

**Development Workflow:** If you develop please look at our [dev workflow](dev-workflow.md)

The `gh-pages` branch contains demo HTML files that point to CDN versions of external packages so people can play with the demos.
`gh-pages` is periodically merged from `master` when new features are released.


---

# Original Aloha Readme follows.

---


# [Aloha Editor - The HTML5 WYSIWYG Editor](http://aloha-editor.org/)

## New Documentation

We're currently writing new [new guides](http://aloha-editor.org/guides). You can find these at **<repos>/doc/guides/output** and on our website: [http://aloha-editor.org](http://aloha-editor.org)


For help there is:
- [the Aloha Editor wiki](https://github.com/alohaeditor/Aloha-Editor/wiki) for end-users and implementors
- [the Aloha Editor guides](http://www.alohaeditor.org/guides/) for developers

- [the issues tracker](https://github.com/alohaeditor/Aloha-Editor/issues) for developer support requests
- [the support forum](http://getsatisfaction.com/aloha_editor) for end-user and implementor support requests
- IRC #alohaeditor @ freenode.net (We are there every Wednesday 9:00 to 18:00 GMT+1)


To get updates you can:
- Subscribe to GitHub updates by clicking the "watch" button up the top right of this page.
- Subscribe to RSS feed updates for the [dev branch](https://github.com/alohaeditor/Aloha-Editor/commits/dev.atom) and/or [master branch](https://github.com/alohaeditor/Aloha-Editor/commits/master.atom)


## Repository Directory Structure

* /bin - Build scripts
* /build - Build configuration
* /doc
* /doc/api - The API documentation
* /doc/guides - This document
* /vendor - Vendor source code. (e.g. ExtJS, require-js, jquery)
* /target - Build output folder
* /src
* /src/css - Aloha core css files
* /src/demo - Aloha demos
* /src/img - Aloha core images
* /src/lib - Require plugins and bootstrap files
* /src/lib/aloha - Main Aloha Editor core sources
* /src/lib/vendor - Vendor source code. E.g. ExtJS, jquery
* /src/lib/util - Utility sources. (e.g. json2.js, class.js)
* /src/plugins
* /src/plugins/common - Common plugin bundle
* /src/plugins/extra - Extra plugin bundle
* /src/test - QUnit tests

## Feeds

- Subscribe to RSS feed updates for the [dev branch](https://github.com/alohaeditor/Aloha-Editor/commits/dev.atom) and/or [master branch](https://github.com/alohaeditor/Aloha-Editor/commits/master.atom)