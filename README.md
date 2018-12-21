This [Composer](https://getcomposer.org) project template is a quick way to install
the [Apigee Developer Portal Kickstart installation profile](https://www.drupal.org/project/apigee_devportal_kickstart)
for Drupal.

This is a Composer package that installs the following components to make a fully working and configured site:
* [Drupal Core](https://www.drupal.org)
* [Apigee Developer Portal Kickstart installation profile](https://www.drupal.org/project/apigee_devportal_kickstart)

# Prerequisites

* [Git](https://git-scm.com)
* [Composer](https://getcomposer.org)

# Installation

The following command will download Drupal core and the Apigee Developer Portal Kickstart profile into
the MY_PROJECT directory:

```
composer create-project apigee/devportal-kickstart-project MY_PROJECT
```

The actual webroot will be MY_PROJECT/web. You will need to point your web server to serve up that
directory and run the installer like any Drupal site installation.

If you want to quickly evaluate the system you  can alternatively run the following command to run
Drupal using PHP's built in web server and a SQLite database:

```
cd MY_PROJECT
composer quick-start
```

# Disclaimer

This is not an officially supported Google product.
