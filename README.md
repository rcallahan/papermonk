# papermonk

Use **papermonk** to extract bibliometric data (including a link to the pdf)
from publishers, while also downloading pdfs and journals, including
supplementary materials.

# install

With [npm](http://npmjs.org/) do:

```
npm install -g papermonk
```

Alternatively, install from git:

```
npm install git://github.com/kanzure/papermonk.git
```

or from a local git repo:

```
git clone git@github.com:kanzure/papermonk.git papermonk
cd papermonk/
npm install .
```

# usage

``` js
var papermonk = require("papermonk");

var options = {
    pdf: true,
}

papermonk.download("http://httpbin.org/get", options, function(bibliometricdata, pdfstream) {
    console.log("metadata: " + bibliometricdata);
});
```

# testing

TODO

# TODO

* papermonk tests

* example module

* example module testing

# license

BSD
