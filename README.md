Buckle
======

Pure JS ZIP extractor, that preserves file attributes. Based on a modified version of DecompressZip.

``` js

var buckle = require('buckle');

buckle.open('/path/to/package.zip', '/destination/path', function(err, result) {
  console.log(err || result);
})
```

That's pretty much it.

Credits
-------

Written by Tomás Pollak.

Copyright
---------

(c) 2014 Fork Ltd. MIT licensed.