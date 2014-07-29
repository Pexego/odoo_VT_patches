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

Odoo
----

Odoo is a suite of web based open source business apps.  More info at http://www.odoo.com

The easiest way to play with it is the <a href="https://www.odoo.com/page/start">Odoo free trial</a>, email registration is NOT required, use the "skip this step" link on the registration page to skip it.


Getting started with Odoo development
--------------------------------------

If you are a developer type the following command at your terminal [1]:

    wget -O- https://raw.githubusercontent.com/odoo/odoo/master/odoo.py | python

Then follow <a href="https://doc.openerp.com/trunk/server/howto/howto_website/">the developer tutorial</a>

[1] You may want to check the content of the <a href="https://raw.githubusercontent.com/odoo/odoo/master/odoo.py">odoo.py file</a> before executing it.


Packages, tarballs and installers
---------------------------------

* Debian packages

    Add this apt repository to your /etc/apt/sources.list file

        deb http://nightly.openerp.com/8.0/deb/ ./

    Then type:

        $ sudo apt-get update
        $ sudo apt-get install odoo

* <a href="http://nightly.openerp.com/">Source tarballs</a>

* <a href="http://nightly.openerp.com/">Windows installer</a>

* <a href="http://nightly.openerp.com/">RPM package</a>


For Odoo employees
------------------

To add the odoo-dev remote use this command:

    $ ./odoo.py setup_git_dev

To fetch odoo merge pull requests refs use this command:

    $ ./odoo.py setup_git_review

