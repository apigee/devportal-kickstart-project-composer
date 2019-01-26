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
composer create-project apigee/devportal-kickstart-project:8.x-dev MY_PROJECT --stability dev --no-interaction
```

The actual web root will be MY_PROJECT/web. You will need to point your web server to serve up that
directory and run the installer like any Drupal site installation.

If you want to quickly evaluate the system you can alternatively run the composer `quick-start` script to run
the [Drupal 8 quick start command](https://www.drupal.org/docs/8/install/drupal-8-quick-start-command):

```
cd MY_PROJECT
composer quick-start
```

This will start Drupal using PHP's built in web server and a SQLite database.

# Issues, Questions and Feedback
We encourage anyone with feedback, questions or issues to put in an issue into
our [Github issue queue](https://github.com/apigee/devportal-kickstart-project-composer/issues).

# Contribute
We'd love to accept your patches and contributions to this project. Make sure to read [CONTRIBUTING.md](CONTRIBUTING.md) for details.
Development is happening in our [GitHub repository](https://github.com/apigee/devportal-kickstart-project-composer).

# Disclaimer

This is not an officially supported Google product.
