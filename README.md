ansible-drupal
==============

Ansible role for installing a Drupal site

Role Variables
--------------

* **drupal.install_dir** - The root directory where the website is installed.
* **drupal.project_name** - Subdirectory where the Drupal site is installed and the name used to set the site config file name.
* **drupal.site_name** - Used as the Drupal site title.

* **drupal.db_host** - Host where the database server is.
* **drupal.db_name** - Name of database to use for the site.
* **drupal.db_user** - The user to login with.
* **drupal.db_pass** - The password to use when logging in.

* **drupal.server_url** - The hostname Nginx should respond to. Multiple hosts can be expressed as a space seperated list string.

Dependencies
------------

* ansible-drush

License
-------

Apache v2
