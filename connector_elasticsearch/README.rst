=======================
connector_elasticsearch
=======================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:429d672085712e961707c5726b16969c11b731a584242bb350d1aed78a06f7c5
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fsearch--engine-lightgray.png?logo=github
    :target: https://github.com/OCA/search-engine/tree/16.0/connector_elasticsearch
    :alt: OCA/search-engine
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/search-engine-16-0/search-engine-16-0-connector_elasticsearch
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/search-engine&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This addon provides the bases to implement addons to export information to
Elasticsearch_ indexes.

.. _Elasticsearch: https://www.elastic.co/

**Table of contents**

.. contents::
   :local:

Changelog
=========

12.0.?.?.? (unreleased)
~~~~~~~~~~~~~~~~~~~~~~~

* connector_elasticsearch: Makes the config on index required only if the
  index is linked to an elastisearch backend. This change allows the usage
  of algolia search engine at the same time as elasticsearch.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/search-engine/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/search-engine/issues/new?body=module:%20connector_elasticsearch%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* ACSONE SA/NV

Contributors
~~~~~~~~~~~~

* Laurent Corron <laurentcorron@gmail.com>
* Laurent Mignon <laurent.mignon@acsone.eu>
* Raphaël Reverdy <raphael.reverdy@akretion.com>
* Simone Orsi <simone.orsi@camptocamp.com>
* Iván Todorovich <ivan.todorovich@camptocamp.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/search-engine <https://github.com/OCA/search-engine/tree/16.0/connector_elasticsearch>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
