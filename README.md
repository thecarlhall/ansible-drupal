ansible-drupal
==============

Ansible role for installing a Drupal site

Role Variables
--------------

* drupal.install_dir - The directory where the website is installed.
* drupal.project_name
* drupal.site_name

* drupal.db_user
* drupal.db_pass
* drupal.db_name

* drupal.server_url - The hostname Nginx should respond to. Multiple hosts can be expressed as a space seperated list.

Dependencies
------------

* ansible-drush

License
-------

Apache v2
