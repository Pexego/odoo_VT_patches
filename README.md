[![Build Status](http://runbot.odoo.com/runbot/badge/flat/1/8.0.svg)](http://runbot.odoo.com/runbot)
[![Tech Doc](http://img.shields.io/badge/8.0-docs-8f8f8f.svg?style=flat)](http://www.odoo.com/documentation/8.0)
[![Help](http://img.shields.io/badge/8.0-help-8f8f8f.svg?style=flat)](https://www.odoo.com/forum/help-1)
[![Nightly Builds](http://img.shields.io/badge/8.0-nightly-8f8f8f.svg?style=flat)](http://nightly.odoo.com/)

Odoo
----

Odoo is a suite of web based open source business apps.

The main Odoo Apps include an <a href="https://www.odoo.com/page/crm">Open Source CRM</a>, <a href="https://www.odoo.com/page/website-builder">Website Builder</a>, <a href="https://www.odoo.com/page/e-commerce">eCommerce</a>, <a href="https://www.odoo.com/page/project-management">Project Management</a>, <a href="https://www.odoo.com/page/accounting">Billing &amp; Accounting</a>, <a href="https://www.odoo.com/page/point-of-sale">Point of Sale</a>, <a href="https://www.odoo.com/page/employees">Human Resources</a>, Marketing, Manufacturing, Purchase Management, ...

Odoo Apps can be used as stand-alone applications, but they also integrate seamlessly so you get
a full-featured <a href="https://www.odoo.com">Open Source ERP</a> when you install several Apps.


Getting started with Odoo
-------------------------
For a standard installation please follow the <a href="https://www.odoo.com/documentation/8.0/setup/install.html">Setup instructions</a>
from the documentation.

If you are a developer you may type the following command at your terminal:

    wget -O- https://raw.githubusercontent.com/odoo/odoo/8.0/odoo.py | python

Then follow <a href="https://www.odoo.com/documentation/8.0/tutorials.html">the developer tutorials</a>


For Odoo employees
------------------

To add the odoo-dev remote use this command:

    $ ./odoo.py setup_git_dev

To fetch odoo merge pull requests refs use this command:

    $ ./odoo.py setup_git_review

[![Build Status](http://runbot.odoo.com/runbot/badge/default/1/8.0.svg)](http://runbot.odoo.com/runbot)

Cambios
-------

29/07/2014 --> actualizado branch odoo_patches_8_0_RC para arreglar un error(https://github.com/odoo/odoo/issues/1223)
    ahora existen las ramas upstream/ que pertenecen al repositorio original.
    https://help.github.com/articles/syncing-a-fork
