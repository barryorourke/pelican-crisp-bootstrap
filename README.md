pelican-crisp-rewrite
=====================

a rewrite of the Crisp Ghost theme using bootstrap, for Pelican!

## Prerequisites

* [python](http://python.org) and [pip](https://pypi.python.org/pypi/pip).
* [nodejs](http://nodejs.org) and [npm](http://www.npmjs.com).
* [ruby](http://ruby-lang.com) and [bundler](http://bundler.io).
* a local copy of the [pelican-plugins](https://github.com/getpelican/pelican-plugins) repository.

## Installing dependencies

```
npm -g install bower
bundle install
bower install
pip install webassets
```

## Configure Pelican

You'll need to modify your *pelicanconf.py* to include the assets plugin, something like this should do the job:

```
PLUGIN_PATH = '/path/to/pelican/plugins/directory'
PLUGINS = ['assets']
```

### Credits

The original inspiration came from Kathy Qian's [Crisp](https://github.com/kathyqian/crisp-ghost-theme) theme for Ghost.
I also used parts of Bootstrap Zero's [Basis](http://www.bootstrapzero.com/bootstrap-template/basis) template to get the fixed sidebar working with bootstrap.
