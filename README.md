Available scripts:

    bundle:norequire
      browserify -e entry.js -o bundle.js && node bundle.js
    bundle:require
      browserify -r 'needsShimName' -e entry.js -o bundle.js && node bundle.js

`bundle:norequire` works. `bundle:require` does not.
