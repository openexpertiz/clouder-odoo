Clouder - Hosting your Apps with Docker and Odoo
------------------------------------------------

`Clouder`_ is a platform which aim to standardize good practices for hosting open-source software. Whether you are launching a hosting offer, are the sysadmin of a company, or just want to host software for you and your friends, Clouder will allow you to easily deploy and maintain a professionnal infrastructure with very basic technical knowledge.

More specifically, Clouder is an orchestrator which is based on the Docker container technology. Each application will be installed inside a container and Clouder will establish links between them. Clouder is based on Odoo, an open-source software application which is very efficient at managing this kind of workflow and process.

Odoo - From ERP to CRM, eCommerce to CMS
----------------------------------------

`Odoo`_ is an all-in-one business management suite of mobile-friendly web apps that integrates everything you need to grow your business: CRM, website content management, project management, human resources, accounting, invoicing and more. Odoo apps integrate seamlessly to provide a full-featured open source ERP, but can also be used stand-alone.

This appliance includes all the standard features in `TurnKey Core`_:

- Odoo v8 installed from upstream GIT source (`GitHub/Odoo`_)
- Clouder v8.1 installed from upstream GIT source (`GitHub/Clouder`_)
- Includes all base modules from base install of Odoo and Clouder
- SSL support out of the box.
- `Adminer`_ administration frontend for PostgreSQL (listening on port 12322 - uses SSL).
- Webmin modules for configuring Apache2, PHP and PostgreSQL.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH: username **root**
-  PostgreSQL, Adminer: username **postgres**
-  Odoo Master Account: **admin**

.. _Odoo: https://www.odoo.com/
.. _Clouder: https://goclouder.net/
.. _GitHub/Odoo: https://github.com/odoo/odoo
.. _GitHub/Clouder: https://github.com/clouder-community/clouder
.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org/
