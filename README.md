Token Help
==========

This module creates two administrative pages with information about tokens provided by other modules:

* **Tokens** at admin/reports/tokens — a listing of all tokens provided by all modules. This is  like the Drupal page that was at admin/help/token but was removed in Backdrop when the admin Help menu was removed.

* **Token Developer Info** at admin/reports/token-developer-info — a table of all of the developer information returned by function [`token_info()`](https://docs.backdropcms.org/api/backdrop/core%21includes%21token.inc/function/token_info/1), consisting of token type, name, description data,  and "needs-data", which indicates that the token chains to another set of tokens.

Users must have the "access administration pages" permission to access either of these pages.

Installation
------------

- Install this module using [the official Backdrop CMS instructions](  https://backdropcms.org/guide/modules).

Issues
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/token_help/issues).

Current Maintainers
-------------------

- [Robert J. Lang](https://github.com/bugfolder)

Credits
-------

- Written for Backdrop CMS by [Robert J. Lang](https://github.com/bugfolder).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.

