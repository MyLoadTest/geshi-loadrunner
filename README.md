LoadRunner Syntax Highlighting for PHP
======================================

The "c_loadrunner.php" file is a GeSHi syntax highlighting file that gives C source code the same colours that are used by VuGen.

More information on [LoadRunner Syntax Highlighting](http://www.myloadtest.com/loadrunner-syntax-highlighter/) is available on my website.

About GeSHi
-----------

GeSHi is the Generic Syntax Highlighter, a PHP library that converts plain text source code to HTML. Source code elements are coloured according to the specified language definition (like the one in "c_loadrunner.php").

* [GeSHi website](https://qbnz.com/highlighter/)

Syntax Highlighting on WordPress
--------------------------------

If you run a WordPress-based website or blog, you can easily highlight LoadRunner code with the WP-Syntax plugin. Just copy "c_loadrunner.php" to the wp-content/plugins/wp-syntax/geshi/geshi directory, and wrap code blocks with &lt;pre lang="c_loadrunner" line="1"&gt; and &lt;/pre&gt;. I have used it [here](http://www.myloadtest.com/loadrunner-syntax-highlighter/).

* [WP-Syntax](http://wordpress.org/extend/plugins/wp-syntax/)