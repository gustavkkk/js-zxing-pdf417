# js-zxing-pdf417
I wanted to be able to find and decode PDF417 in browser so we did a port of the excelent http://github.com/zxing/zxing PDF417 decoder.

It works with excellent quality images but additional work is needed to make it detect PDF417's more reliably but in many tests it now works better than Zxing.

Demo
----
http://peculiarventures.github.io/js-zxing-pdf417

Build
-----

  npm install
  
  grunt


Requirements
------------
This library depends on https://github.com/peterolson/BigInteger.js
