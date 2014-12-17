[![Build Status](https://travis-ci.org/OpenUpgrade/OpenUpgrade.svg?branch=8.0)](https://travis-ci.org/OpenUpgrade/OpenUpgrade)

Odoo
----

Odoo is a suite of web based open source business apps.

It's main apps include an <a href="https://www.odoo.com/page/crm">Open Source CRM</a>, <a href="https://www.odoo.com/page/website-builder">Website Builder</a>, <a href="https://www.odoo.com/page/e-commerce">eCommerce</a>, <a href="https://www.odoo.com/page/project-management">Project Management</a>, <a href="https://www.odoo.com/page/accounting">Billing & Accounting</a>, <a href="https://www.odoo.com/page/point-of-sale">Point of Sale</a>, <a href="https://www.odoo.com/page/employees">Human Resources</a>, Marketing, Manufacturing, Purchase Management, ...  Each application is standalone but you get a full featured <a href="https://www.odoo.com">Open Source ERP</a> if you install several apps as they integrate to each others.


Getting started with Odoo development
--------------------------------------

If you are a developer type the following command at your terminal:

    wget -O- https://raw.githubusercontent.com/odoo/odoo/master/odoo.py | python

Then follow <a href="https://doc.openerp.com/trunk/server/howto/howto_website/">the developer tutorial</a>



Packages, tarballs and installers
---------------------------------

* Debian packages

    Add this apt repository to your /etc/apt/sources.list file

        deb http://nightly.openerp.com/8.0/nightly/deb/ ./

    Then type:

        $ sudo apt-get update
        $ sudo apt-get install openerp

    If you plan to use Odoo with a local database, please make sure to install PostgreSQL *before* installing the Odoo Debian package.

* <a href="http://nightly.openerp.com/8.0/nightly/src/">Source tarballs</a>

* <a href="http://nightly.openerp.com/8.0/nightly/exe/">Windows installer</a>

* <a href="http://nightly.openerp.com/8.0/nightly/rpm/">RPM package</a>


For Odoo employees
------------------

To add the odoo-dev remote use this command:

    $ ./odoo.py setup_git_dev

To fetch odoo merge pull requests refs use this command:

    $ ./odoo.py setup_git_review
