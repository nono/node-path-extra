Node.js: path-extra
===================

This module simply modifies the Node.js 'path' object with extra methods. It is a drop in replacement for the `path` module.



Installation
------------

    $ npm install path-extra



Usage
-----

```javascript
var path = require('path-extra');
```

You can still use all of the vanilla Node.js path methods.

Methods:

```javascript
path.tempdir() // returns a temporary directory that is operating system specific
path.homedir() // returns the user's home directory
path.datadir(appname) // returns a directory to store data in for an app with the given name
```



License
-------

(The MIT License)

Copyright (c) 2011-2015 JP Richardson




