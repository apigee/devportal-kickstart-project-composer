# Apigee Developer Portal Kickstart Composer Project

This [Composer](https://getcomposer.org) project template is a quick way to install the [Apigee Developer Portal Kickstart installation profile](https://www.drupal.org/project/apigee_devportal_kickstart) for Drupal.

This is a Composer package that installs the following components to make a fully working and configured site:

* [Drupal Core](https://www.drupal.org)
* [Apigee Developer Portal Kickstart installation profile](https://www.drupal.org/project/apigee_devportal_kickstart)

## Prerequisites

* [Git](https://git-scm.com)
* [Composer](https://getcomposer.org)

## Installation

The following command will download Drupal core, the Apigee Developer Portal Kickstart profile, and their dependencies, into the `MY_PROJECT` directory:

```sh
composer create-project apigee/devportal-kickstart-project:8.x-dev MY_PROJECT --no-interaction
```

The actual web root will be `MY_PROJECT/web`. You will need to point your [web server](https://www.drupal.org/docs/develop/local-server-setup) to serve that directory. Then, visit the site in a web browser, and you'll be redirected to `core/install.php`, where you can run the installer like any Drupal site installation. Running the installation via web browser is recommended for the best experience.

Alternatively, you may run the composer `quick-start` script to run the [Drupal 8 Quick Start Command](https://www.drupal.org/docs/8/install/drupal-8-quick-start-command). This will install Drupal using PHP's built in web server and an SQLite database.*

```sh
cd MY_PROJECT
composer quick-start
```

**Note: While `quick-start` is the quickest means of installing this profile, it is not the most performant, or complete. It does not present the configuration options available when installing via web browser. As a result, you'll need to configure the [Apigee Edge connection](https://www.drupal.org/docs/8/modules/apigee-edge/configure-the-connection-to-apigee-edge) manually, post installation. See [Apigee Edge documentation](https://www.drupal.org/docs/8/modules/apigee-edge) for more details.*

## Issues, Questions and Feedback

We encourage anyone with feedback, questions or issues to put in an issue into our [Github issue queue](https://github.com/apigee/devportal-kickstart-project-composer/issues).

## Contribute

We'd love to accept your patches and contributions to this project. Make sure to read [CONTRIBUTING.md](CONTRIBUTING.md) for details. Development is happening in our [GitHub repository](https://github.com/apigee/devportal-kickstart-project-composer).

## Support

This project, which integrates Drupal 8 with Apigee Edge, is supported by Google.
