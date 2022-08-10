Token Help
==========

This module creates two administrative pages with information about tokens provided by other modules:

* **Tokens** at admin/reports/tokens — a listing of all tokens provided by all modules. This is  like the Drupal page that was at admin/help/token but was removed in Backdrop when the admin Help menu was removed.

* **Token Developer Info** at admin/reports/token-developer-info — a table of all of the developer information returned by function [`token_info()`](https://docs.backdropcms.org/api/backdrop/core%21includes%21token.inc/function/token_info/1), consisting of token type, name, description data,  and "needs-data", which indicates that the token chains to another set of tokens.

Users must have the "access administration pages" permission to access either of these pages.

Installation
------------

Install this module using [the official Backdrop CMS instructions](  https://backdropcms.org/guide/modules).

This module uses the standard system token browser for the **Tokens** page. For sites with large numbers of tokens (particularly if the [Entity Tokens](https://backdropcms.org/project/entity_token) module is installed), the **Tokens** page can take a long time to load or not load at all (this can also happen in other places where the system token browser is used). If you encounter this issue, the [Fast Token Browser](https://backdropcms.org/project/fast_token_browser) replaces the standard system token browser with a click-to-expand listing that renders much more efficiently.

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

