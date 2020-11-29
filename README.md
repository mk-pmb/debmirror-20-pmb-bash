
<!--#echo json="package.json" key="name" underline="=" -->
debmirror-20-pmb
================
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
Another approach to mirroring debian package repositories, created in 2020.
<!--/#echo -->



Usage
-----

:TODO:



Config
------

### Wordlist rules

1.  Lines with "#" anywhere in them are ignored.
1.  Text in round parens (`()`) is ignored, too.
    * You can use this to help your editor sort lines by stuff like
      version numbers.
1.  Remaining words are split by whitespace and used as values.







<!--#toc stop="scan" -->



Known issues
------------

* Needs more/better tests and docs.




&nbsp;


License
-------
<!--#echo json="package.json" key=".license" -->
ISC
<!--/#echo -->
