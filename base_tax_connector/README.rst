|License AGPL-3| | |Build Status| | |Test Coverage|

==================
Tax Connector Base
==================


Installation
============


Configuration
=============


Known Issues / Road Map
=======================

* In order for rates to work, the reference record must actually be saved.
  This is because the reference fields require explicit ``(model_name,id)``
  formatting, but with an unsaved record the ID is ``NewId``.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues
<https://github.com/LasLabs/odoo-connector-taxjar/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smash it by providing detailed and welcomed feedback.

Credits
=======

Contributors
------------

* Dave Lasley <dave@laslabs.com>

Do not contact contributors directly about support or help with technical issues.

Maintainer
----------

.. image:: https://laslabs.com/logo.png
   :alt: LasLabs Inc.
   :target: https://laslabs.com

This module is maintained by LasLabs Inc.


.. |Build Status| image:: https://img.shields.io/travis/LasLabs/odoo-connector-taxjar/master.svg
   :target: https://travis-ci.org/LasLabs/odoo-connector-taxjar
.. |Test Coverage| image:: https://img.shields.io/codecov/c/github/LasLabs/odoo-connector-taxjar/master.svg
   :target: https://codecov.io/gh/LasLabs/odoo-connector-taxjar
.. |License AGPL-3| image:: https://img.shields.io/badge/license-AGPL--3-blue.svg
   :target: https://www.gnu.org/licenses/agpl
   :alt: License: AGPL-3
