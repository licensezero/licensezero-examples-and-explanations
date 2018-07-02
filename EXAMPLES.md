Have a look at [`README.md`](./README.md) before diving in here.

___Reading these examples without reading [Parity] and [Prosperity] for yourself is a big, dangerous mistake.___

These examples and explanations have not been written with the same precision as the licenses.  They also unavoidably express someone's _opinion_ about the meaning of the licenses, and how their language would play out in more or less specific scenarios.  No one---no developer using [Parity] or [Prosperity], no developer or company using work licensed under those terms, and no court---has to agree with the conclusions found here.

Jump to:
[developer tools](#developer-tools) |
[libraries](#libraries) |
[web platforms](#web-platforms) |
[frameworks](#frameworks) |
[interpreters](#interpreters) |
[other applications](#other)

[Parity]: https://licensezero.com/licenses/parity

[Prosperity]: https://licensezero.com/licenses/prosperity

[private license]: https://licensezero.com/licenses/private

# <a id="developer-tools">Developer Tools</a>

## Browserify

<https://browserify.org>

Browserify compiles JavaScript programs that require npm packages into bundles of code for web browsers.  Developers user Browserify to combine their own code with code from others' packages to make applications that run in the browser.

### Browserify Under [Parity]

Developers using Browserify to bundle programs would have to release all source code for those programs, as software they have analyzed, changed, or otherwise made using Browserify, under Rule 3:

    3. Release all source code for software that you analyze,
       change, or otherwise make using this software.

Developers building Browserify into other applications, like <https://wzrd.in/>, which offers Browserified versions of npm packages via CDN, would have to release all source code for their larger programs, under Rule 2:

    2. If you run or combine this software with other software in
       any larger program, release all source code for that program.

Developers of Browserify transforms, like [Deassertify](https://www.npmjs.com/package/deassertify), which strips test assertions out of Browserified bundles, would have to release source code for their transforms, also under Rule 2.  Likewise for developers of Browserify plugins, like [browserify-hmr](https://www.npmjs.com/package/browserify-hmr), which implements hot module replacement.

Developers making changes to Browserify, perhaps to improve its performance or support new kinds of dependencies, would have to release source code for their improved versions, under Rule 1:

    1. Release source code for changes you make to this software.

### Browserify Under [Prosperity]

Developers using Browserify for nonmcommercial purposes, like hobbyists, charities, and academics doing research primarily to advance public knowledge, could do so without any time limit or requirement to release source code.

Those using Browserify for commercial purposes would have to limit their use to a built-in free trial of 32 days, under Rule 1:

    1. You must limit use of this software in any manner primarily
       intended for or directed toward commercial advantage or
       private monetary compensation to a trial period of 32
       consecutive calendar days. This limit does not apply to use in
       developing feedback, modifications, or extensions that you
       contribute back to those giving this license.

## Standard

<https://standardjs.com/>

Standard reports style errors in JavaScript source code.  With a flag, it can also automatically correct many style errors.  Developers use Standard to check the style of their code, often by configuring npm or Git to run it on all code in every commit.

### Standard Under [Parity]

Developers using Standard to check and fix style in code for a program  would have to release all source code for that program, as software they have analyzed and possibly changed, under Rule 3:

    3. Release all source code for software that you analyze,
       change, or otherwise make using this software.

Developers building Standard into other applications, like online code editors or code-quality assessment tools, would have to release all source code for their larger programs, under Rule 2:

    2. If you run or combine this software with other software in
       any larger program, release all source code for that program.

Developers making changes to Standard, perhaps to improve its performance or customize its style rules, would have to release source code for their versions, under Rule 1:

    1. Release source code for changes you make to this software.

### Standard Under [Prosperity]

Developers using Standard for nonmcommercial purposes, like hobbyists, charities, and academics doing research primarily to advance public knowledge, could do so without any time limit or requirement to release source code.

Those using Standard for commercial purposes would have to limit their use to a built-in free trial of 32 days, under Rule 1:

    1. You must limit use of this software in any manner primarily
       intended for or directed toward commercial advantage or
       private monetary compensation to a trial period of 32
       consecutive calendar days. This limit does not apply to use in
       developing feedback, modifications, or extensions that you
       contribute back to those giving this license.

## npm

<https://www.npmjs.com>

npm installs and manages dependencies for JavaScript software projects.  Developers use npm to download open source packages to use in their work, and also to manage their own work as packages.

### npm Under [Parity]

TODO

### npm Under [Prosperity]

TODO

## GCC

<https://gcc.gnu.org/>

GCC compiles source code.

### GCC Under [Parity]

TODO

### GCC Under [Prosperity]

TODO

## Atom

<https://atom.io/>

Atom is a full-featured graphical text editor with robust theme and plugin systems.

### Atom Under [Parity]

TODO

### Atom Under [Prosperity]

TODO

# <a id="libraries">Libraries</a>

## jQuery

<https://jquery.com/>

jQuery is a library for manipulating the Document Object Models of web browsers.

### jQuery Under [Parity]

TODO

### jQuery Under [Prosperity]

TODO

## node-semver

<https://www.npmjs.com/package/semver>

node-semver is a library for parsing and analyzing semantic version numbers for software releases.

### node-semver Under [Parity]

TODO

### node-semver Under [Prosperity]

TODO

## Express.js

<https://expressjs.com/>

Express.js is a library for creating Node.js HTTP servers with a straightforward, approachable API.

### Express.js Under [Parity]

TODO

### Express.js Under [Prosperity]

TODO

# <a id="databases">Databases</a>

## MongoDB

<https://www.mongodb.com>

MongoDB is a networked database for document objects with a rich query API.

### MongoDB Under [Parity]

TODO

### MongoDB Under [Prosperity]

TODO

## SQLite

<https://sqlite.org>

SQLite is an embeddable SQL database built into programs as a library.

### SQLite Under [Parity]

TODO

### SQLite Under [Prosperity]

TODO

# <a id="web-platforms">Web Platforms</a>

## WordPress

<https://wordpress.com/>

WordPress is a platform for hosting weblogs.

### WordPress Under [Parity]

TODO

### WordPress Under [Prosperity]

TODO

# <a id="frameworks">Frameworks</a>

## Ruby on Rails

<https://rubyonrails.org/>

Ruby on Rails is a framework for building Ruby web applications.

### Ruby on Rails Under [Parity]

TODO

### Ruby on Rails Under [Prosperity]

TODO

# <a id="interpreters">Interpreters</a>

## Python

<https://www.python.org/>

Python is an interpreter for a popular programming language.

### Python Under [Parity]

TODO

### Python Under [Prosperity]

TODO

## Clojure

<https://clojure.org/>

Clojure is a programming language built (initially) on top of the Java Virtual Machine, often loaded as a Maven dependency.

### Clojure Under [Parity]

TODO

### Clojure Under [Prosperity]

TODO

# <a id="other">Other Applications</a>

## Inkscape

<https://inkscape.org/en/>

Inskcape is a full-featured editor for vector graphics.

### Inkscape Under [Parity]

TODO

### Inkscape Under [Prosperity]

TODO

## GitLab

<https://gitlab.com/>

GitLab is an web application for hosting and collaborating on source code.

### GitLab Under [Parity]

TODO

### GitLab Under [Prosperity]

TODO
